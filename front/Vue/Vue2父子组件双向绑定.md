# Vue2父子组件通信

> 需求：使用Vue2，把父子组件的变量进行绑定。让子组件的数据改变时，父组件的数据也可以改变，反之亦然。

*\!\!注意，语法糖：[语法糖](https://so.csdn.net/so/search?q=语法糖&spm=1001.2101.3001.7020)（Syntactic Sugar）是编程中的一个概念，指的是一种在语法上更简洁、更易读、更易书写，但实际上并没有引入新的功能或特性的语法结构。它们不会改变语言的功能，只是使代码更具可读性和易用性。语法糖可以让代码更清晰，更接近人类语言，减少了开发者的负担。*

## 两个前置知识

### 自定义事件

使用$emit（）可以定义一个自己的事件和传递的值，我原本使用的就是这个方式，来传递子组件的值到父组件的。父组件中引用方式如下。我们自己在父组件定义一个接受数据的函数，然后监听事件（在当前组件触发一个自定义事件。任何额外的参数都会传递给事件监听器的回调函数。）

```Vue
<pageInputNo @updateSelect="receiveShip" msgHdrName="ShipInfo" :isMultiSelection="false" selectKey="shipCode" selectValue="shipCode" :labelList="labelListShipInfo" :fieldList="fieldListShipInfo"></pageInputNo>

export default{
  methods:{
     receiveShip(e){
			console.log("shipCode: ", e);
			this.form.shipCode = e.shipCode
			this.form.shipCodeBrief = e.name
		},
}
}


<!--以下时子组件内的代码-->
			radioChange: function(evt) {
				for (let i = 0; i < this.selectItems.length; i++) {
					//console.log('evt.detail.value::' + evt.detail.value + ',selectKey:' + this.selectKey);
					if (this.selectItems[i][this.selectKey] == evt.detail.value) {
						this.selectedIndex = i;
						// 返回下拉框选择项数据到父组件
						this.$emit('updateSelect', this.selectItems[i])
						break;
					}
				}
				this.$refs.popup.close()

			},
```

### .sync

这是一个Vue语法糖，**`.sync`修饰符可以像`v-model`一样实现类似双向绑定的场景用法。组件间修改某一个值，和同一个组件中修改一个值**。我们用`$emit('update:xx', 参数)`的形式传参，因为如果不用这种方法子组件内的`props`参数将无法成功修改，而是没有反应，所以Vue官方建议我们在子组件触发传递父组件事件中也同样用`update:xx`这种写法。当使用 `.sync` 修饰符时，子组件在数据发生变化时，会触发一个特定格式的事件（`update:属性名`），父组件会自动监听这个事件并更新相应的数据。

```vue
父组中有子组件传值
<child :title.sync="msg"></child>


子中试图修改这个值，实现父子值传递双向绑定。
<button @click="setTitle">点击修改父组件信息</button>
props:["title"],
methods:{
    setTitle(){
        this.$emit("update:title",Date.now())/*固定写法*/
    }
}

```

## 解决方法

```vue
					<pageInputNo v-model="form.shipTypeCode" :brief.sync="form.shipTypeCodeBrief" msgHdrName="ShipType" :isMultiSelection="false" selectKey="shipTypeCode" selectValue="shipTypeCode" :labelList="labelListShipType" :fieldList="fieldListShipType"></pageInputNo>

```

父组件中我们用v-model先绑定一个值，然后用.sync修饰另一个需要双向绑定的值```:brief.sync="form.shipTypeCodeBrief"```同时也使用了v-bind绑定了父组件中的变量

```vue

<script>
	import {
		getList
	} from '@/api/common.js';

	export default {
		name: 'DrawerInputButtonComponent',
		props: {
			// v-model默认绑定value，如需变更需要使用model: {prop: 'xx', event: 'xx'}
			value: {
				type: String,
				default: 'model的val'
			},
			brief: {
				type: String,
				default: 'model的Brief'
			},
			

		},
		data() {
			return {
				valBrief: '',
				localDataTypeCode: this.dataTypeCode,
				localDataTypeCodeBrief: this.dataTypeCodeBrief,
				//.........省略无关参数
			};
		},
		computed: {
			innerValue: {
				get() {
					console.log('get::', this.value);
					return this.value; // 直接返回父组件的值
				},
				set(newVal) {
					console.log('set::', newVal);
					this.$emit('input', newVal); // 触发input事件更新父组件数据
				}
			}
		},

		watch: {
			localDataTypeCode(newValue) {
				console.log('code改变', newValue);
				this.$emit('update:dataTypeCode', newValue);
			},
			localDataTypeCodeBrief(newValue) {
        console.log('codeBrief改变', newValue);
        this.$emit('update:dataTypeCodeBrief', newValue);
      },
		},

		methods: {

			radioChange: function(evt) {
				for (let i = 0; i < this.selectItems.length; i++) {
					//console.log('evt.detail.value::' + evt.detail.value + ',selectKey:' + this.selectKey);
					if (this.selectItems[i][this.selectKey] == evt.detail.value) {
						this.selectedIndex = i;
						this.localDataTypeCodeBrief = this.selectItems[i][this.selectValue];
						this.localDataTypeCode = this.selectItems[i][this.selectKey];
						this.innerValue = this.selectItems[i][this.selectKey];
						console.log('name::', this.selectItems[i].name);
						this.valBrief = this.selectItems[i].name;
						this.handleChange();
						break;
					}
				}
				this.$refs.popup.close()

			},
			
			handleChange(newVal) {
				// 计算额外值（例如：输入内容是否有效）
				// 触发 update:extraProp 事件，更新父组件的 extraProp 值
				this.$emit('update:brief', this.valBrief);
			}
		}
	};
</script>

<style scoped>
	.sel {
		height: 600px;
	}

	.nosel {
		width: 33vw;
		height: 30px;
	}

	.lable {
		display: flex;

	}

	.search {
		display: flex;
		padding-left: 5px;
		padding-right: 5px;
		width: 100vw;
	}
</style>
```

* 使用computed（用于声明要在组件实例上暴露的计算属性）声明要监听的属性,这里传递的是code

  ```js
  		computed: {
  			innerValue: {
  				get() {
  					console.log('get::', this.value);
  					return this.value; // 直接返回父组件的值
  				},
  				set(newVal) {
  					console.log('set::', newVal);
  					this.$emit('input', newVal); // 触发input事件更新父组件数据
  				}
  			}
  		},
  ```

* 然后定义```handleChange```函数自定义一个update：xx的事件，然后.sync监听所有的update:xx的事件。我们运行了```this.valBrief = this.selectItems[i].name;```之后，使用```handleChange```函数触发update:brief事件，事件会被.sync监听,值会被brief接收。

  ```js
  		radioChange: function(evt) {
  			for (let i = 0; i < this.selectItems.length; i++) {
  				//console.log('evt.detail.value::' + evt.detail.value + ',selectKey:' + this.selectKey);
  				if (this.selectItems[i][this.selectKey] == evt.detail.value) {
  					this.selectedIndex = i;
  					this.localDataTypeCodeBrief = this.selectItems[i][this.selectValue];
  					this.localDataTypeCode = this.selectItems[i][this.selectKey];
  					this.innerValue = this.selectItems[i][this.selectKey];
  					console.log('name::', this.selectItems[i].name);
  					this.valBrief = this.selectItems[i].name;
  					this.handleChange();
  					break;
  				}
  			}
  			this.$refs.popup.close()
  
  		},
  		
  		handleChange(newVal) {
  			// 计算额外值（例如：输入内容是否有效）
  			// 触发 update:extraProp 事件，更新父组件的 extraProp 值
  			this.$emit('update:brief', this.valBrief);
  		}
  ```

  