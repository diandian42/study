### v-if和v-show

v-show：

* 原理是修改容器的css，```display:none```
* 既是v-show使得容器不显示，在页面中容器也会存在
* 适合的场景：频繁切换容器的显示与隐藏状态

v-if：

* 原理是基于条件判断，是否创建元素或者删除元素
* 适合场景：要么显示，要么隐藏



### v-if和v-else-if

![image-20250301105418800](C:\Users\11988\AppData\Roaming\Typora\typora-user-images\image-20250301105418800.png)

就和我们的if-else语句一样的

### v-on

* 注册事件（监听DOM事件） = 添加监听 + 提供处理逻辑

* 语法：

  * v-on ：事件名 = “内联语句”
  * v-on ：事件名 = “methods中的函数名”

* 简写：@事件名

* 你还可以将一个函数绑定到动态的事件名称上：

  ```
  <a v-on:[eventName]="doSomething"> ... </a>
  
  <!-- 简写 -->
  <a @[eventName]="doSomething"> ... </a>
  ```

  在此示例中，当 `eventName` 的值是 `"focus"` 时，`v-on:[eventName]` 就等价于 `v-on:focus`

* v-on调用传参：@事件名=“函数名（参数1，参数2...）”![image-20250301110928403](C:\Users\11988\AppData\Roaming\Typora\typora-user-images\image-20250301110928403.png)

### v-bind

* 动态的设置标签属性 -》src、url等
* 语法：v-bind:属性名=“表达式”![image-20250301112052527](C:\Users\11988\AppData\Roaming\Typora\typora-user-images\image-20250301112052527.png)



### v-for

* 作用：基于数据循环，多次渲染整个元素  --》数组、对象、数字。。。。
* 语法：v-for=“（item，index）” in 数组
* v-for的key
  * key属性 = “唯一标识”
  * 给列表添加唯一标识。方便vue进行正确的排序复用![image-20250301114950458](C:\Users\11988\AppData\Roaming\Typora\typora-user-images\image-20250301114950458.png)
  * v-for默认会原地修改元素（不加key）
  * key的值只能是字符串或者数字类型
  * key的值必须有唯一性



### v-model

* 作用：给表单元素使用的，做双向数据绑定 -》可以快速获得、设置表单内容
  * 数据变化 -》 视图自动更新
  * 视图变化 -》 数据自动更新