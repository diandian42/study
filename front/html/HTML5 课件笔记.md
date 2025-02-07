

# HTML5

## 什么是HTML5



### 定义

```
万维网的核心语言、标准通用标记语言下的一个应用超文本标记语言（HTML）的第五次重大修改
```

### 环境

```
支持Html5的浏览器包括Firefox（火狐浏览器），IE9及其更高版本，Chrome（谷歌浏览器），Safari，Opera等；国内的傲游浏览器（Maxthon），以及基于IE或Chromium（Chrome的工程版或称实验版）所推出的360浏览器、搜狗浏览器、QQ浏览器、猎豹浏览器等国产浏览器同样具备支持HTML5的能力
```

### 目的

```
HTML5的设计目的是为了在移动设备上支持多媒体。新的语法特征被引进以支持这一点，如video、audio和canvas 标记。HTML5还引进了新的功能，可以真正改变用户与文档的交互方式
```

### 新增特性

```
增加了新特性：语义特性，本地存储特性，设备兼容特性，连接特性，网页多媒体特性，三维、图形及特效特性，性能与集成特性, 地理定位, 设备权限与功能，CSS3特性
session、 video、 audio、 worker、 canvas、SVG requestAnimationFrame、 history、 file Reader、 Full Screen、 Page Visibility、 getUserMedia API、Battery API、Link Prefetching、orientationchange、navigator.vibrate、navigator.language 、navigator.onLine、contentEditable 、window.onblur & window.onfocus、loaction
```

### 对比HTML4

```
相比之前的进步：取消了一些过时的HTML4标记，将内容和展示分离，一些全新的表单输入对象，全新的，更合理的Tag，本地数据库，Canvas 对象，浏览器中的真正程序，Html5取代Flash在移动设备的地位
```

#### 优点

- 提高可用性和改进用户的友好体验；

- 有几个新的标签，这将有助于开发人员定义重要的内容；

- 可以给站点带来更多的多媒体元素(视频和音频)；

- 可以很好的替代FLASH和Silverlight；

- 当涉及到网站的抓取和索引的时候，对于[SEO](http://baike.baidu.com/view/1047.htm)很友好；

- 将被大量应用于移动应用程序和游戏；

- 可移植性好。

#### 缺点

​	随着标签功能与对应API的复杂化 , 各浏览器厂商在规则的实践上存在差异, 兼容性需要控制。



### HTML5中的新增标签

为了更好地处理今天的互联网应用，HTML5添加了很多新元素及功能，比如： 图形的绘制，多媒体内容，更好的页面结构，更好的形式 处理，和几个api拖放元素，定位，包括网页 应用程序缓存，存储，网络工作者，等。

canvas

| ***\*标签\**** | ***\*描述\****                                               |
| -------------- | ------------------------------------------------------------ |
| <canvas>       | 标签定义图形，比如图表和其他图像。该标签基于 JavaScript 的绘图 API |

多媒体

| 标签     | 描述                                                       |
| -------- | ---------------------------------------------------------- |
| <audio>  | 定义音频内容                                               |
| <video>  | 定义视频（video 或者 movie）                               |
| <source> | 定义多媒体资源 <video> 和 <audio> 字体                     |
| <embed>  | 定义嵌入的内容，比如插件。                                 |
| <track>  | 为诸如 <video> 和 <audio> 元素之类的媒介规定外部文本轨道。 |

表单

| 标签       | 描述                                                         |
| ---------- | ------------------------------------------------------------ |
| <datalist> | 定义选项列表。请与 input 元素配合使用该元素，来定义 input 可能的值。 |
| <keygen>   | 规定用于表单的密钥对生成器字段。                             |
| <output>   | 定义不同类型的输出，比如脚本的输出。                         |

语义和结构

HTML5提供了新的元素来创建更好的页面结构：

| ***\*标签\**** | ***\*描述\****                                               |
| -------------- | ------------------------------------------------------------ |
| <article>      | 定义页面的侧边栏内容                                         |
| <aside>        | 定义页面内容之外的内容。                                     |
| <bdi>          | 允许您设置一段文本，使其脱离其父元素的文本方向设置。         |
| <command>      | 定义命令按钮，比如单选按钮、复选框或按钮                     |
| <details>      | 用于描述文档或文档某个部分的细节                             |
| <dialog>       | 定义对话框，比如提示框                                       |
| <summary>      | 标签包含 details 元素的标题                                  |
| <figure>       | 规定独立的流内容（图像、图表、照片、代码等等）。             |
| <figcaption>   | 定义 <figure> 元素的标题                                     |
| <footer>       | 定义 section 或 document 的页脚。                            |
| <header>       | 定义了文档的头部区域                                         |
| <mark>         | 定义带有记号的文本。                                         |
| <meter>        | 定义度量衡。仅用于已知最大和最小值的度量。                   |
| <nav>          | 定义运行中的进度（进程）。                                   |
| <progress>     | 定义任何类型的任务的进度。                                   |
| <ruby>         | 定义 ruby 注释（中文注音或字符）。                           |
| <rt>           | 定义字符（中文注音或字符）的解释或发音。                     |
| <rp>           | 在 ruby 注释中使用，定义不支持 ruby 元素的浏览器所显示的内容。 |
| <section>      | 定义文档中的节（section、区段）。                            |
| <time>         | 定义日期或时间。                                             |
| <wbr>          | 规定在文本中的何处适合添加换行符。                           |

 

### HTML中移除的标签：

以下的 HTML 4.01 元素在HTML5中已经被删除:

Ø <acronym> 字体兼容

Ø <applet> java组件

Ø <basefont> 字体

Ø <big>

Ø <center>

Ø <dir> 目录

Ø <font>

Ø <frame>

Ø <frameset>

Ø <noframes>

Ø <strike>



### 元素分类

**根元素**

`html`  `:root`

**元数据元素**

`head、base、meta、title、link、style`

**分区元素**

`body、header、footer、aside、main、nav、section、article、h1~h6、hgroup、address`

**块元素**

`div、p、ol、ul、li、dd、dl、dt、hr、blockquote、figcaption、figure`

**内联文本元素**

`a、span、br、abbr、cite、code、small、time、bdi、bdo`

`data、dfn、kbd、mark、q、rb、rp、rt、rtc、ruby、samp、u、var、wbr`

**媒体元素**

`audio、img、video、map、track、area`

**内嵌元素**

`embed、iframe、object、param、picture、source`

**脚本元素**

`canvas、script、noscript `

**编辑标识元素**

`del、ins`

**表格元素**

`table、caption、thead、tbody、tfoot、tr、th、td、colgroup、col `

**表单元素**

`form、label、input、button、select、datalist、optgroup、option、textarea、fieldset、legend、meter、output、progress `

**交互元素**

`details、dialog、menu、summary `

**Web** 组件

`template、slot `

### HTML5中的新增语义结构标签

| 标签       | 描述                                             |
| :--------- | :----------------------------------------------- |
| article    | 定义页面独立的内容区域。                         |
| aside      | 定义页面的侧边栏内容。                           |
| figure     | 规定独立的流内容（图像、图表、照片、代码等等）。 |
| figcaption | 定义 <figure> 元素的标题                         |
| footer     | 定义 section 或 document 的页脚。                |
| header     | 定义了文档的头部区域                             |
| mark       | 定义带有记号的文本。                             |
| nav        | 定义导航链接的部分。                             |
| section    | 定义文档中的节（section、区段）。                |
|            | 定义文档主体内容区域                             |



1. 传统页面的标签使用

2. HTML5页面中的标签使用，如：

```html
<body>
    <header>定义了文档的头部区域</header>
    <div>
        <article>定义页面的侧边栏内容</article>
        <aside>定义页面内容之外的内容</aside>
    </div>
    <footer>定义 section 或 document 的页脚</footer>
</body>
```

 

### 兼容处理：

>  在不支持HTML5新标签的浏览器里，会将这些新的标签解析成行内元素(inline)对待，所以我们只需要将其转换成块元素(block)即可使用，但是在IE9版本以下，并不能正常解析这些新标签，但是却可以识别通过document.createElement('tagName')创建的自定义标签，于是我们的解决方案就是将HTML5的新标签全部通过document.createElement('tagName')来创建一遍，这样IE低版本也能正常解析HTML5新标签了。

####  处理方式：

在实际开发中我们更多采用的是通过检测IE浏览器的版本来加载三方的一个JS库来解决兼容问题（测试在IE下面的兼容性：ieTester软件的使用）

<script src="../js/html5shiv.min.js"></script>

 



### HTML5中新增标签全局属性

| 属性                | 描述                                                   |
| :------------------ | :----------------------------------------------------- |
| contenteditable     | 规定元素内容是否可编辑。                               |
| contextmenu(不兼容) | 规定元素的上下文菜单。上下文菜单在用户点击元素时显示。 |
| data-*              | 用于存储页面或应用程序的私有定制数据。                 |
| draggable           | 规定元素是否可拖动。                                   |
| dropzone            | 规定在拖动被拖动数据时是否进行复制、移动或链接。       |
| hidden              | 规定元素仍未或不再相关。                               |
| spellcheck          | 规定是否对元素进行拼写和语法检查。                     |
| translate           | 规定是否应该翻译元素内容。                             |



### HTML5中新增的功能标签

#### mark

> 突出显示部分文本：

```html
<p>我是一个小红帽, 我非常<mark>可爱</mark> .</p>
```

<p>我是一个小红帽, 我非常<mark>可爱</mark> .</p>



#### meter

> 使用 meter 元素来度量给定范围（gauge）内的数据：

```html
<meter value="3" min="0" max="10">十分之三</meter>

<meter value="0.6">60%</meter> 
```

<meter value="3" min="0" max="10">十分之三</meter>

<meter value="0.6">60%</meter> 

| 属性    | 值        | 描述                                    |
| :------ | :-------- | :-------------------------------------- |
| form    | *form_id* | 规定 <meter> 元素所属的一个或多个表单。 |
| high    | *number*  | 规定被视作高的值的范围。                |
| low     | *number*  | 规定被视作低的值的范围。                |
| max     | *number*  | 规定范围的最大值。                      |
| min     | *number*  | 规定范围的最小值。                      |
| optimum | *number*  | 规定度量的优化值。                      |
| value   | *number*  | 必需。规定度量的当前值。                |



#### output

> 显示输出结果(无法编辑)。

```html
<output>$100</output>
```



#### dataList

>定义下拉列表 datalist 元素规定输入域的选项列表。列表是通过 datalist 内的 option 元素创建的。如需把 datalist 绑定到输入域，请用输入域的 list 属性引用 datalist 的 id：

```html
网址: <input type="url" list="url_list" name="link" >
<datalist id="url_list">
<option label="Baidu" value="http://www.baidu.com" >
<option label="Google" value="http://www.google.com" >
<option label="Microsoft" value="http://www.microsoft.com" >
</datalist>
```



#### progress

> 进度条

```html
<progress value="22" max="100"></progress> 
```

<progress value="22" max="100"></progress> 



| 属性  | 值       | 描述                       |
| :---- | :------- | :------------------------- |
| max   | *number* | 规定任务一共需要多少工作。 |
| value | *number* | 规定已经完成多少任务。     |



#### ruby&rt&rp

> <rt> 标签定义字符（中文注音或字符）的解释或发音。
>
> ruby 注释是中文注音或字符。
>
> 在东亚使用，显示的是东亚字符的发音。
>
> 与 <ruby> 以及 <rt> 标签一同使用：
>
> ruby 元素由一个或多个字符（需要一个解释/发音）和一个提供该信息的 rt 元素组成，还包括可选的 rp 元素，定义当浏览器不支持 "ruby" 元素时显示的内容。

```html
<ruby>汉<rt>Hàn</rt><rp>han</rp></ruby>
```

<ruby>汉<rt>Hàn</rt><rp>han</rp></ruby>



#### details&summary

> details 标签用于描述文档或文档某个部分的细节。 summary 标签包含 details 元素的标题，"details" 元素用于描述有关文档或文档片段的详细信息。

```html
<details>
<summary>HTML 5</summary>
HTML5是一个非常好的版本
</details>
```

<details>
<summary>HTML 5</summary>
HTML5是一个非常好的版本
</details>



#### time

> time 标签定义公历的时间（24 小时制）或日期，时间和时区偏移是可选的。
>
> 该元素能够以机器可读的方式对日期和时间进行编码，这样，举例说，用户代理能够把生日提醒或排定的事件添加到用户日程表中，搜索引擎也能够生成更智能的搜索结果。

```html
<p>我们在每天早上 <time>9:00</time> 开始营业。</p>

<p>我在 <time datetime="2008-02-14">情人节</time> 有个约会。</p>
```

<p>我们在每天早上 <time>9:00</time> 开始营业。</p>

<p>我在 <time datetime="2008-02-14">情人节</time> 有个约会。</p>



#### wbr

> Word Break Opportunity (wbr) 规定在文本中的何处适合添加换行符。
>
> 如果单词太长，或者您担心浏览器会在错误的位置换行，那么您可以使用 <wbr> 元素来添加 Word Break Opportunity（单词换行时机）。

```html
<p>如果想学习 AJAX，那么您必须熟悉 XML<wbr>Http<wbr>Request 对象。</p>
```

<p>如果想学习 AJAX，那么您必须熟悉 XML<wbr>Http<wbr>Request 对象。</p>








### 表单的输入类型

##### Input 类型: color

color 类型用在input字段主要用于选取颜色，如下所示：

##### Input 类型: date

date 类型允许你从一个日期选择器选择一个日期。

##### Input 类型: datetime

datetime 类型允许你选择一个日期（UTC 时间）。

##### Input 类型: datetime-local

datetime-local 类型允许你选择一个日期和时间 (无时区).

##### Input 类型: email

email 类型用于应该包含 e-mail 地址的输入域。

##### Input 类型: month

month 类型允许你选择一个月份。

##### Input 类型: number

number 类型用于应该包含数值的输入域。

| 属性      | 描述                       |
| :-------- | :------------------------- |
| disabled  | 规定输入字段是禁用的       |
| max       | 规定允许的最大值           |
| maxlength | 规定输入字段的最大字符长度 |
| min       | 规定允许的最小值           |
| pattern   | 规定用于验证输入字段的模式 |
| readonly  | 规定输入字段的值无法修改   |
| required  | 规定输入字段的值是必需的   |
| size      | 规定输入字段中的可见字符数 |
| step      | 规定输入字段的合法数字间隔 |
| value     | 规定输入字段的默认值       |

##### Input 类型: range

range 类型用于应该包含一定范围内数字值的输入域。

range 类型显示为滑动条。

请使用下面的属性来规定对数字类型的限定：

- max - 规定允许的最大值
- min - 规定允许的最小值
- step - 规定合法的数字间隔
- value - 规定默认值

##### Input 类型: search

search 类型用于搜索域，比如站点搜索或 Google 搜索。

##### Input 类型: tel

定义输入电话号码字段:

电话号码: <input type="tel" name="usrtel">

##### Input 类型: time

time 类型允许你选择一个时间。

##### Input 类型: url

url 类型用于应该包含 URL 地址的输入域。

在提交表单时，会自动验证 url 域的值。

##### Input 类型: week

week 类型允许你选择周和年。



### HTML5表单新增的属性

##### **placeholder**

>  占位符 

##### **autofocus**

> 获取焦点

##### **multiple** 

> 文件上传多选或多个邮箱地址  

##### **autocomplete** 

> 自动完成，用于表单元素，也可用于表单自身

##### **form**

> 指定表单项属于哪个form，处理复杂表单时会需要

##### **novalidate** 

> 关闭验证，可用于<form>标签

##### **required** 

> 验证条件，必填项

##### **pattern** 

> 正则表达式 验证表单

##### accept

> 在文件上传中使用 accept 属性，设置接收的类型 如果不限制图像的格式，可以写为：accept="image/*"。

```html
<form>
  <input type="file" name="pic" id="pic" accept="image/gif, image/jpeg" />
</form>
```





```html
<form action="" autocomplete="on">
    autofocus定位文本框焦点：<input type="text" autofocus> <br>
    placeholder设置文本框默认提示：<input type="text" placeholder="请输入***"><br>
    email邮件类型自带验证和提示：<input type="email"> <br>
    required属性设置非空特性：<input type="tel" required><br>
    pattern设置验证规则：<input type="tel" name="tel" required pattern="^(\+86)?1[358]\d{5}$"><br>
    multiple多文件选择：<input type="file" multiple><br>
    <input type="submit" value="提交"/>
</form>
```



### HTML5新增DOM API

#### 获取元素

```js
document.getElementsByClassName ('class') 通过类名获取元素，以伪数组形式存在。
document.querySelector('selector') 通过CSS选择器获取元素，符合匹配条件的第1个元素。
document.querySelectorAll('selector') 通过CSS选择器获取元素，以伪数组形式存在。复制代码
```

#### 类名操作

```js
Node.classList.add('class') 添加class
Node.classList.remove('class') 移除class
Node.classList.toggle('class') 切换class，有则移除，无则添加
Node.classList.contains('class') 检测是否存在class复制代码
```

Node指一个有效的DOM节点，是一个通称。

#### 自定义属性

在HTML5中我们可以自定义属性，其格式如下data-*=""，例如

```js
data-info="我是自定义属性"复制代码
```

通过Node.dataset['info'] 我们便可以获取到自定义的属性值。

Node.dataset是以对象形式存在的，当我们为同一个DOM节点指定了多个自定义属性时，Node.dataset则存储了所有的自定义属性的值。

假设某元素 <div id="demo" data-name="itcast" data-age="10">

var demo = document.querySelector('#demo');

1、读取 demo.dataset['name'] 或者 demo.dataset['age']

2、设置demo.dataset['name'] = 'web developer'

注：当我们如下格式设置时，则需要以驼峰格式才能正确获取

<div data-my-name="itcast"> 这样获取Node.dataset['myName']



#### after


> **`ChildNode.after()`** 方法会在其父节点的子节点列表中插入一些 [`Node`](https://developer.mozilla.org/zh-CN/docs/Web/API/Node) 或 [`DOMString`](https://developer.mozilla.org/zh-CN/docs/Web/API/DOMString) 对象。插入位置为该节点之后。[`DOMString`](https://developer.mozilla.org/zh-CN/docs/Web/API/DOMString) 对象会被以 [`Text`](https://developer.mozilla.org/zh-CN/docs/Web/API/Text) 的形式插入。

```js
[Throws, Unscopable] 
void ChildNode.after((Node or DOMString)... nodes);

let parent = document.createElement("div");
let child = document.createElement("p"); 
parent.appendChild(child); 
let span = document.createElement("span");

child.after(span, "Text"); 

console.log(parent.outerHTML);
// "<div><p></p><span></span>Text</div>"
```

#### before

>  `ChildNode`**`.before`** 方法可以在`ChildNode这个节点的父节点中插入一些列的` [`Node`](https://developer.mozilla.org/zh-CN/docs/Web/API/Node) 或者 [`DOMString`](https://developer.mozilla.org/zh-CN/docs/Web/API/DOMString) 对象，位置就是在`ChildNode节点的前面，`[`DOMString`](https://developer.mozilla.org/zh-CN/docs/Web/API/DOMString) 对象其实和 [`Text`](https://developer.mozilla.org/zh-CN/docs/Web/API/Text)节点一样的方式来完成插入的。

```js
[Throws, Unscopable] 
void ChildNode.before((Node or DOMString)... nodes);

let parent = document.createElement("div");
let child = document.createElement("p");
parent.appendChild(child);
let span = document.createElement("span");

child.before(span);

console.log(parent.outerHTML);
// "<div><span></span><p></p></div>"
```

#### remove

> `**ChildNode.remove()**` 方法，把对象从它所属的 DOM 树中删除。

```js
node.remove();

let oBox = document.querySelector('.box');
oBox.remove();
```

#### replaceWith

>`**ChildNode**`**`.replaceWith()`** 的方法用一套 [`Node`](https://developer.mozilla.org/zh-CN/docs/Web/API/Node) 对象或者 [`DOMString`](https://developer.mozilla.org/zh-CN/docs/Web/API/DOMString) 对象，替换了该节点父节点下的子节点 。[`DOMString`](https://developer.mozilla.org/zh-CN/docs/Web/API/DOMString) 对象被当做等效的[`Text`](https://developer.mozilla.org/zh-CN/docs/Web/API/Text) 节点插入。

```js
[Throws, Unscopable] 
void ChildNode.replaceWith((Node or DOMString)... nodes);


let parent = document.createElement("div");
let child = document.createElement("p");
parent.appendChild(child);
let span = document.createElement("span");

child.replaceWith(span);

console.log(parent.outerHTML);
// "<div><span></span></div>"
```

#### append

>  **`ParentNode.append`** 方法在 `ParentNode`的最后一个子节点之后插入一组 [`Node`](https://developer.mozilla.org/zh-CN/docs/Web/API/Node) 对象或 [`DOMString`](https://developer.mozilla.org/zh-CN/docs/Web/API/DOMString) 对象。
>
> 被插入的 [`DOMString`](https://developer.mozilla.org/zh-CN/docs/Web/API/DOMString) 对象等价为 [`Text`](https://developer.mozilla.org/zh-CN/docs/Web/API/Text) 节点。

```js

与 Node.appendChild() 的差异：
ParentNode.append()允许追加  DOMString 对象，而 Node.appendChild() 只接受 Node 对象。
ParentNode.append() 没有返回值，而 Node.appendChild() 返回追加的 Node 对象。
ParentNode.append() 可以追加多个节点和字符串，而 Node.appendChild() 只能追加一个节点。

[Throws, Unscopable] 
void ParentNode.append((Node or DOMString)... nodes);
```

```js
var parent = document.createElement("div");
var p = document.createElement("p");
parent.append("Some text", p);

console.log(parent.childNodes); // NodeList [ #text "Some text", <p> ]
```

#### prepend

> **`ParentNode.prepend`** 方法可以在父节点的第一个子节点之前插入一系列[`Node`](https://developer.mozilla.org/zh-CN/docs/Web/API/Node)对象或者[`DOMString`](https://developer.mozilla.org/zh-CN/docs/Web/API/DOMString)对象。[`DOMString`](https://developer.mozilla.org/zh-CN/docs/Web/API/DOMString)会被当作[`Text`](https://developer.mozilla.org/zh-CN/docs/Web/API/Text)节点对待（也就是说插入的不是HTML代码）。

```js
ParentNode.prepend((Node or DOMString)... nodes);

let parent = document.createElement("div");
let p = document.createElement("p");
let span = document.createElement("span");
parent.append(p);
parent.prepend(span);

console.log(parent.childNodes); // NodeList [ <span>, <p> ]
```

#### replaceChildren [firefox safari]

> 方法将一个 [`Node`](https://developer.mozilla.org/zh-CN/docs/Web/API/Node) 的后代替换为指定的后代集合。这些新的后代可以为 [`DOMString`](https://developer.mozilla.org/zh-CN/docs/Web/API/DOMString) 或 [`Node`](https://developer.mozilla.org/zh-CN/docs/Web/API/Node) 对象。 

```js
ParentNode.replaceChildren(...nodesOrDOMStrings) // 返回 undefined

//清空一个节点
//replaceChildren()为清空一个节点的后代提供了非常方便的机制，您只需在父节点不指定任何实参调用该方法即可。

myNode.replaceChildren(); //清空myNode的后代
```

### HTML5 拖拽drag drop拖放事件

> 拖放（Drag 和 drop）是 HTML5 标准的组成部分。

#### 定义和用法

ondragstart 事件在用户开始拖动元素或选择的文本时触发。

**注意：** 为了让元素可拖动，需要使用 HTML5 draggable 属性。

**提示：** 链接和图片默认是可拖动的，不需要 draggable 属性。

在拖放的过程中会触发以下事件：

- 在拖动目标上触发事件
  - ondragstart - 用户开始拖动元素时触发
  - ondrag - 元素正在拖动时触发
  - ondragend - 用户完成元素拖动后触发
- 释放目标时触发的事件:
  - ondragenter - 当被鼠标拖动的对象进入其容器范围内时触发此事件
  - ondragover- 当某被拖动的对象在另一对象容器范围内拖动时触发此事件
  - ondragleave - 当被鼠标拖动的对象离开其容器范围内时触发此事件
  - ondrop- 在一个拖动过程中，释放鼠标键时触发此事件



### video 视频

> H5 插入 video 多媒体标签 <video></video>

#### 属性

| 属性                           | 值                             | 描述                                                         |
| :----------------------------- | :----------------------------- | :----------------------------------------------------------- |
| autoplay                       | autoplay                       | 如果出现该属性，则视频在就绪后马上播放。                     |
| controls                       | controls                       | 如果出现该属性，则向用户显示控件，比如播放按钮。             |
| height                         | *pixels*                       | 设置视频播放器的高度。                                       |
| loop                           | loop                           | 如果出现该属性，则当媒介文件完成播放后再次开始播放。         |
| muted                          | muted                          | 如果出现该属性，视频的音频输出为静音。                       |
| poster                         | *URL*                          | 规定视频正在下载时显示的图像，直到用户点击播放按钮。         |
| preload                        | auto metadata none             | 如果出现该属性，则视频在页面加载时进行加载，并预备播放。如果使用 "autoplay"，则忽略该属性。 |
| src                            | *URL*                          | 要播放的视频的 URL。                                         |
| width                          | *pixels*                       | 设置视频播放器的宽度。                                       |
| playsinline/webkit-playsinline | playsinline/webkit-playsinline | Iphone ios/ 微信浏览器支持小窗内播放                         |
| volume                         | double                         | 表示音频的音量。值从0.0（静音）到1.0（最大音量）。           |
| paused                         | boolean                        | 是否已暂停                                                   |
| muted                          | boolean                        | 设置或返回音频/视频是否静音                                  |
| playbackRate                   | double                         | 音频/视频的当前播放速度。  1.0 正常速度 0.5 半速（更慢） 2.0 倍速（更快） |
| duration                       | number                         | 数字值，表示音频/视频的长度，以秒计。                        |
| readyState                     | boolean                        | 返回视频是否就绪                                             |

#### 方法

| 方法                                                         | 描述                                    |
| :----------------------------------------------------------- | :-------------------------------------- |
| addTextTrack() | 向音频/视频添加新的文本轨道             |
| canPlayType() | 检测浏览器是否能播放指定的音频/视频类型 |
| load()  | 重新加载音频/视频元素                   |
| play()  | 开始播放音频/视频                       |
| pause() | 暂停当前播放的音频/视频                 |

#### 事件

> video元素可以触发以下事件

| 事件名称            | 描述                                                         |
| :------------------ | :----------------------------------------------------------- |
| `abort`             | 在播放被终止时触发,例如, 当播放中的视频重新开始播放时会触发这个事件。 |
| `canplay`           | 在媒体数据已经有足够的数据（至少播放数帧）可供播放时触发。这个事件对应CAN_PLAY的readyState。 |
| `canplaythrough`    | 在媒体的readyState变为CAN_PLAY_THROUGH时触发，表明媒体可以在保持当前的下载速度的情况下不被中断地播放完毕。注意：手动设置currentTime会使得firefox触发一次canplaythrough事件，其他浏览器或许不会如此。 |
| `durationchange`    | 元信息已载入或已改变，表明媒体的长度发生了改变。例如，在媒体已被加载足够的长度从而得知总长度时会触发这个事件。 |
| `emptied`           | 媒体被清空（初始化）时触发。                                 |
| `ended`             | 播放结束时触发。                                             |
| `error`             | 在发生错误时触发。元素的error属性会包含更多信息。参阅 [HTMLMediaElement.error](https://developer.mozilla.org/en-US/docs/Web/API/HTMLMediaElement/error) 获得详细信息。 |
| `interruptbegin`    | 声音在Firefox OS设备中断时触发,可能是应用程序被切换至后台或者更高优先级的应用占用了音频通道。 相关信息请参考 [Using the AudioChannels API](https://developer.mozilla.org/en-US/docs/Web/API/AudioChannels_API/Using_the_AudioChannels_API) |
| `interruptend`      | 声音在Firefox OS设备中断后恢复播放时触发,应用程序被切换至前台或占用更高级音频通道的应用程序播放完毕后触发。相关信息请参考 [Using the AudioChannels API](https://developer.mozilla.org/en-US/docs/Web/API/AudioChannels_API/Using_the_AudioChannels_API) |
| `loadedmetadata`    | 媒体的元数据已经加载完毕，现在所有的属性包含了它们应有的有效信息。 |
| `loadstart`         | 在媒体开始加载时触发。                                       |
| `mozaudioavailable` | 当音频数据缓存并交给音频层处理时                             |
| `pause`             | 播放暂停时触发。                                             |
| `play`              | 在媒体回放被暂停后再次开始时触发。即，在一次暂停事件后恢复媒体回放。 |
| `playing`           | 在媒体开始播放时触发（不论是初次播放、在暂停后恢复、或是在结束后重新开始）。 |
| `progress`          | 告知媒体相关部分的下载进度时周期性地触发。有关媒体当前已下载总计的信息可以在元素的buffered属性中获取到。 |
| `ratechange`        | 在回放速率变化时触发。                                       |
| `seeked`            | 在跳跃操作完成时触发。                                       |
| `seeking`           | 在跳跃操作开始时触发。                                       |
| `stalled`           | 在尝试获取媒体数据，但数据不可用时触发。                     |
| `suspend`           | 在媒体资源加载终止时触发，这可能是因为下载已完成或因为其他原因暂停。 |
| `timeupdate`        | 元素的currentTime属性表示的时间已经改变。                    |
| `volumechange`      | 在音频音量改变时触发（既可以是volume属性改变，也可以是muted属性改变）.。 |
| `waiting`           | 在一个待执行的操作（如回放）因等待另一个操作（如跳跃或下载）被延迟时触发。 |



```html
<!-- Simple video example -->
<video src="videofile.ogg" autoplay poster="posterimage.jpg">
  抱歉，您的浏览器不支持内嵌视频，不过不用担心，你可以 <a href="videofile.ogg">下载</a>
  并用你喜欢的播放器观看!
</video>

<!-- Video with subtitles -->
<video src="foo.ogg">
  <track kind="subtitles" src="foo.en.vtt" srclang="en" label="English">
  <track kind="subtitles" src="foo.sv.vtt" srclang="sv" label="Svenska">
</video>
```

浏览器并不是都支持相同的[视频格式](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Supported_media_formats)，所以你可以在 [``](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/source) 元素里提供多个视频源，然后浏览器将会使用它所支持的第一个源。

```html
<video controls>
  <source src="myVideo.mp4" type="video/mp4">
  <source src="myVideo.webm" type="video/webm">
  <p>你的浏览器不支持H5 video播放器 你可以点击链接下载视频
      <a href="myVideo.mp4">点击下载</a> </p>
</video>
```

### audio 音频

> 音频标签  <audio> </audio>

```html
<audio src="mp3/xxx.mp3">
	您的浏览器不支持audio
</audio>
```

#### 属性

| audioTracks         | 返回表示可用音频轨道的 AudioTrackList 对象。        |
| ------------------- | --------------------------------------------------- |
| autoplay            | 设置或返回是否在就绪（加载完成）后随即播放音频。    |
| buffered            | 返回表示音频已缓冲部分的 TimeRanges 对象。          |
| controller          | 返回表示音频当前媒体控制器的 MediaController 对象。 |
| controls            | 设置或返回音频是否应该显示控件（比如播放/暂停等）。 |
| crossOrigin         | 设置或返回音频的 CORS 设置。                        |
| currentSrc          | 返回当前音频的 URL。                                |
| currentTime         | 设置或返回音频中的当前播放位置（以秒计）。          |
| defaultMuted        | 设置或返回音频默认是否静音。                        |
| defaultPlaybackRate | 设置或返回音频的默认播放速度。                      |
| duration            | 返回音频的长度（以秒计）。                          |
| ended               | 返回音频的播放是否已结束。                          |
| error               | 返回表示音频错误状态的 MediaError 对象。            |
| loop                | 设置或返回音频是否应在结束时再次播放。              |
| mediaGroup          | 设置或返回音频所属媒介组合的名称。                  |
| muted               | 设置或返回是否关闭声音。                            |
| networkState        | 返回音频的当前网络状态。                            |
| paused              | 设置或返回音频是否暂停。                            |
| playbackRate        | 设置或返回音频播放的速度。                          |
| played              | 返回表示音频已播放部分的 TimeRanges 对象。          |
| preload             | 设置或返回音频的 preload 属性的值。                 |
| readyState          | 返回音频当前的就绪状态。                            |
| seekable            | 返回表示音频可寻址部分的 TimeRanges 对象。          |
| seeking             | 返回用户当前是否正在音频中进行查找。                |
| src                 | 设置或返回音频的 src 属性的值。                     |
| textTracks          | 返回表示可用文本轨道的 TextTrackList 对象。         |
| volume              | 设置或返回音频的音量。                              |

#### 方法

| 方法           | 描述                                   |
| :------------- | :------------------------------------- |
| addTextTrack() | 向音频添加新的文本轨道。               |
| canPlayType()  | 检查浏览器是否能够播放指定的音频类型。 |
| load()         | 重新加载音频元素。                     |
| play()         | 开始播放音频。                         |
| pause()        | 暂停当前播放的音频。                   |

#### 事件

| 方法                                                         | 描述                                      |
| :----------------------------------------------------------- | :---------------------------------------- |
| addTextTrack() | 向音频/视频添加新的文本轨道。             |
| canPlayType() | 检测浏览器是否能播放指定的音频/视频类型。 |
| load()       | 重新加载音频/视频元素。                   |
| play()       | 开始播放音频/视频。                       |
| pause()     | 暂停当前播放的音频/视频。                 |

### fullScreen全屏

> 通过fullScreen方法接口包括 element全屏 退出全屏 判断全屏状态



#### fullscreenElement

> 判断是否全屏

```
document.fullscreenElement || document.webkitFullscreenElement || document.mozFullScreenElement || document.msFullscreenElement
```

#### requestFullScreen()

> 开启全屏显示

```js
element.requestFullscreen(); //默认标准
element.webkitRequestFullScreen(); //Safari chrome Edge
element.mozRequestFullScreen(); //Firefox
element.msRequestFullscreen(); //IE
```

#### exitFullscreen()

> 退出全屏显示

```js
document.exitFullscreen(); //默认标准
document.webkitCancelFullScreen(); //Safari chrome
document.mozCancelFullScreen(); //Firefox
document.msExitFullscreen(); //IE
document.webkitExitFullscreen();//Safari chrome

```

### FileReader

> FileReader 对象允许Web应用程序异步读取存储在用户计算机上的文件（或原始数据缓冲区）的内容，使用 [`File`](https://developer.mozilla.org/zh-CN/docs/Web/API/File) 或 [`Blob`](https://developer.mozilla.org/zh-CN/docs/Web/API/Blob) 对象指定要读取的文件或数据。



```
其中File对象可以是来自用户在一个<input>元素上选择文件后返回的FileList对象,也可以来自拖放操作生成的 DataTransfer对象,还可以是来自在一个HTMLCanvasElement上执行mozGetAsFile()方法后返回结果。

重要提示： FileReader仅用于以安全的方式从用户（远程）系统读取文件内容 它不能用于从文件系统中按路径名简单地读取文件。 要在JavaScript中按路径名读取文件，应使用标准Ajax解决方案进行服务器端文件读取，如果读取跨域，则使用CORS权限。
```

#### 属性

- [`FileReader.error`](https://developer.mozilla.org/zh-CN/docs/Web/API/FileReader/error) 只读

  一个[`DOMException`](https://developer.mozilla.org/zh-CN/docs/Web/API/DOMException)，表示在读取文件时发生的错误 。

- [`FileReader.readyState`](https://developer.mozilla.org/zh-CN/docs/Web/API/FileReader/readyState) 只读

  表示`FileReader`状态的数字。取值如下：常量名值描述`EMPTY``0`还没有加载任何数据.`LOADING``1`数据正在被加载.`DONE``2`已完成全部的读取请求.

- [`FileReader.result`](https://developer.mozilla.org/zh-CN/docs/Web/API/FileReader/result) 只读

  文件的内容。该属性仅在读取操作完成后才有效，数据的格式取决于使用哪个方法来启动读取操作。

#### 事件处理

##### FileReader.onabort

处理`abort`事件。该事件在读取操作被中断时触发。

##### FileReader.onerror

处理`error`事件。该事件在读取操作发生错误时触发。

##### FileReader.onload

处理`load`事件。该事件在读取操作完成时触发。

##### FileReader.onloadstart

处理`loadstart`事件。该事件在读取操作开始时触发。

##### FileReader.onloadend

处理`loadend`事件。该事件在读取操作结束时（要么成功，要么失败）触发。

##### FileReader.onprogress

处理`progress`事件。该事件在读取[`Blob`](https://developer.mozilla.org/zh-CN/docs/Web/API/Blob)时触发。

#### 方法

##### FileReader.abort()

中止读取操作。在返回时，`readyState`属性为`DONE`。

##### FileReader.readAsArrayBuffer()

开始读取指定的 Blob中的内容, 一旦完成, result 属性中保存的将是被读取文件的 ArrayBuffer 数据对象.

##### FileReader.readAsBinaryString()

开始读取指定的Blob中的内容。一旦完成，`result`属性中将包含所读取文件的原始二进制数据。

##### FileReader.readAsDataURL()

开始读取指定的[`Blob`](https://developer.mozilla.org/zh-CN/docs/Web/API/Blob)中的内容。一旦完成，`result`属性中将包含一个`data:` URL格式的Base64字符串以表示所读取文件的内容。

##### FileReader.readAsText()

开始读取指定的[`Blob`](https://developer.mozilla.org/zh-CN/docs/Web/API/Blob)中的内容。一旦完成，`result`属性中将包含一个字符串以表示所读取的文件内容。

### Blob

`Blob` 对象表示一个不可变、原始数据的类文件对象。它的数据可以按文本或二进制的格式进行读取，也可以转换成 [`ReadableStream`](https://developer.mozilla.org/zh-CN/docs/Web/API/ReadableStream) 来用于数据操作。 

Blob 表示的不一定是JavaScript原生格式的数据。[`File`](https://developer.mozilla.org/zh-CN/docs/Web/API/File) 接口基于`Blob`，继承了 blob 的功能并将其扩展使其支持用户系统上的文件。

要从其他非blob对象和数据构造一个 `Blob`，请使用 [`Blob()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Blob/Blob) 构造函数。要创建一个 blob 数据的子集 blob，请使用 [`slice()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Blob/slice) 方法。要获取用户文件系统上的文件对应的 `Blob` 对象，请参阅 [`File`](https://developer.mozilla.org/zh-CN/docs/Web/API/File) 文档。

#### 构造函数

- [`Blob(blobParts[, options\])`](https://developer.mozilla.org/zh-CN/docs/Web/API/Blob/Blob)

  返回一个新创建的 `Blob` 对象，其内容由参数中给定的数组串联组成。

#### 属性

- [`Blob.size`](https://developer.mozilla.org/zh-CN/docs/Web/API/Blob/size) 只读

  `Blob` 对象中所包含数据的大小（字节）。

- [`Blob.type`](https://developer.mozilla.org/zh-CN/docs/Web/API/Blob/type) 只读

  一个字符串，表明该 `Blob` 对象所包含数据的 MIME 类型。如果类型未知，则该值为空字符串。

#### 方法

- [`Blob.slice([start[, end[, contentType\]]])`](https://developer.mozilla.org/zh-CN/docs/Web/API/Blob/slice)

  返回一个新的 `Blob` 对象，包含了源 `Blob` 对象中指定范围内的数据。

- [`Blob.stream()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Blob/stream)

  返回一个能读取blob内容的 [`ReadableStream`](https://developer.mozilla.org/zh-CN/docs/Web/API/ReadableStream)。

- [`Blob.text()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Blob/text)

  返回一个promise且包含blob所有内容的UTF-8格式的 [`USVString`](https://developer.mozilla.org/zh-CN/docs/Web/API/USVString)。

- [`Blob.arrayBuffer()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Blob/arrayBuffer)

  返回一个promise且包含blob所有内容的二进制格式的 [`ArrayBuffer`](https://developer.mozilla.org/zh-CN/docs/Web/API/ArrayBuffer) 

### sessionStorage 会话存储

> sessionStorage可以存储数据到会话内存  存储容量5m左右 根据浏览器不同可使用空间有略微差别

```js
window.sessionStorage.setItem('time','20:20'); //设置

let time = window.sessionStorage.getItem('time'); //读取
console.log(time); //'20:20'

window.sessionStorage.removeItem('time'); //删除指定key

window.sessionStorage.clear(); //清空

console.log(window.sessionStorage.getItem('time')); //undefined
```

#### 注意

1. 数据本质上存储在当前页面分配内存中, 当关闭当前会话页面 数据会擦除
2. 声明周期与页面的会话周期相同



### localStorage 本地存储

> localStorage 可以存储数据到本地 存储容量20m左右 根据浏览器不同可使用空间有略微差别

```js
window.localStorage.setItem('time','20:20'); //设置

let time = window.localStorage.getItem('time'); //读取
console.log(time); //'20:20'

window.localStorage.removeItem('time'); //删除指定key

window.localStorage.clear(); //清空

console.log(window.localStorage .getItem('time')); //undefined
```

#### 注意

1. 存储内容会放在浏览器程式的文件中(xml) 
2. 永久生效 数据存储在硬盘上 不会随着页面或者浏览器关闭而清除 如果需要清除 需要手动调用方法

### 网络状态

> H5 支持网络状态监听事件

#### online 联网

```js
window.addEventListener('online',function(){
	console.log('联网');
},false)
```

#### offline联网

```js
window.addEventListener('offline',function(){
	console.log('断网');
},false)
```

### 页面状态监听

> window对象提供给我们可以监听页面当前状态事件 :  onload、onpageshow、onpagehide、onbeforeunload、onunload 浏览器跳转、关闭、刷新时都按beforeunload,pagehide,unload,load,pageshow的顺序执行

```js
	window.location.url = 'http://www.baidu.com'　　
// 页面跳转之前执行了beforeunload事件
    window.onbeforeunload = function () {
        localStorage.setItem('beforeunload', 'check');
        return false;
    }
    // 页面隐藏的时候执行了pagehide事件
    window.onpagehide = function () {
         localStorage.setItem('pagehide', 'check')
    }
    // 当用户离开页面时触发了unload事件
    window.onunload = function () {
        localStorage.setItem('unload', 'check')
    }
    // 页面完成加载时执行了load事件
    window.onload = function () {
        localStorage.setItem('load', 'check')
    }
    // 页面显示的时候执行了pageshow事件
    window.onpageshow = function () {
        localStorage.setItem('pageshow', 'check')
    }
```

有时候，开发者需要知道，用户正在离开页面。常用的方法是监听下面三个事件

- `pagehide`
- `beforeunload`
- `unload`

但是，这些事件在手机上可能不会触发，页面就直接关闭了。因为手机系统可以将一个进程直接转入后台，然后杀死。

- 用户点击了一条系统通知，切换到另一个 App。
- 用户进入任务切换窗口，切换到另一个 App。
- 用户点击了 Home 按钮，切换回主屏幕。
- 操作系统自动切换到另一个 App（比如，收到一个电话）。

上面这些情况，都会导致手机将浏览器进程切换到后台，然后为了节省资源，可能就会杀死浏览器进程。为了解决这个问题，就诞生了 Page Visibility API。不管手机或桌面电脑，所有情况下，这个 API 都会监听到页面的可见性发生变化。

这个新的 API 的意义在于，通过监听网页的可见性，可以预判网页的卸载，还可以用来节省资源，减缓电能的消耗。比如，一旦用户不看网页，下面这些网页行为都是可以暂停的。

> - 对服务器的轮询
> - 网页动画
> - 正在播放的音频或视频

#### document.visibilityState

>  API 主要在`document`对象上，新增了一个`document.visibilityState`属性。该属性返回一个字符串，表示页面当前的可见性状态，共有三个可能的值。

```
hidden：页面彻底不可见。
visible：页面至少一部分可见。
prerender：页面即将或正在渲染，处于不可见状态。
```

其中，`hidden`状态和`visible`状态是所有浏览器都必须支持的。`prerender`状态只在支持"预渲染"的浏览器上才会出现，比如 Chrome 浏览器就有预渲染功能，可以在用户不可见的状态下，预先把页面渲染出来，等到用户要浏览的时候，直接展示渲染好的网页。

只要页面可见，哪怕只露出一个角，`document.visibilityState`属性就返回`visible`。只有以下四种情况，才会返回`hidden`。

```
浏览器最小化。
浏览器没有最小化，但是当前页面切换成了背景页。
浏览器将要卸载（unload）页面。
操作系统触发锁屏屏幕。
```

#### isibilitychange 事件

> 只要`document.visibilityState`属性发生变化，就会触发`visibilitychange`事件。因此，可以通过监听这个事件（通过`document.addEventListener()`方法或`document.onvisibilitychange`属性），跟踪页面可见性的变化。

```js
document.addEventListener('visibilitychange', function () {
    if (document.visibilityState == 'hidden') {
        document.title = '页面不可见';
    } else {
        document.title = '页面可见';
    }
});

document.addEventListener('visibilitychange', function() {
    if (document.hidden) {
        document.title = '页面不可见';
    }
    else {
        document.title = '页面可见';
    }
});
```

#### onblur && onfocus

> 在你浏览其他窗口页面、或是浏览器最小化、又或是点击了其他程序等等，都算是浏览器窗口失去焦点，那么 **`window.onblur`** 事件就会触发。
>
> 当你浏览别的窗口或者别的程序,直接点就是当你的窗口失去焦点的时候，就会触发**window.onblur** 
>
> 当你的页面获得焦点的时候一样也会触发**window.onfocus**

```js

window.onblur = function () {
    document.title = "页面失去焦点";
}

window.onfocus = function () {
    document.title = "页面聚焦";
}
```

### 地理信息

> h5提供了地理位置功能（Geolocation API),能确定用户位置，我们可以借助h5的该特性开发基于地理位置信息的应用，本文集合实力给大家分享下如何使用h5，借助百度，谷歌地图接口来获取用户准确的地理位置信息。

#### 基础概念

**地理位置**

•   经度 :  南北极的连接线

•   纬度 :  东西连接的线

**位置信息从何而来**

•   IP地址

•   GPS全球定位系统

•   Wi-Fi无线网络

•   基站

#### API方法

**地理位置对象**

**navigator.geolocation**



单次定位请求 ：getCurrentPosition(请求成功，请求失败，数据收集方式)

```js
if (window.navigator.geolocation) {
    navigator.geolocation.getCurrentPosition(successCallback, errorCallback, options);
} 
```

 **请求成功函数**  successCallback

```js
function successCallback(position) {
    var output = '';
    output += "您的位置已经确定下来\n\n";
    output += '经度：' + position.coords.longtitude + "\n\n";
    output += '纬度：' + position.coords.latitude + "\n\n";
    output += '精度：' + position.coords.accuracy + " 米\n";
    if (position.coords.altitudeAccuracy) {
        output += '海拔精度：' + position.coords.altitudeAccuracy + " 米\n";
    };
    if (position.coords.heading) {
        output += '速度：' + position.coords.Speed + "m/s\n";
    };
    output += '时间戳：' + position.timestamp;
    console.log(output);
}

```

经度 : coords.longitude

纬度 : coords.latitude

准确度 : coords.accuracy

海拔 : coords.altitude

海拔准确度 : coords.altitudeAcuracy

行进方向 : coords.heading

地面速度 : coords.speed

时间戳 : new Date(position.timestamp)

**请求失败函数** errorCallback

```js
function errorCallback(error) {
    console.log(error);
}

// GeolocationPositionError {code: 3, message: "Timeout expired"}

```

失败编号 ：code

0 : 不包括其他错误编号中的错误

1 : 用户拒绝浏览器获取位置信息

2 : 尝试获取用户信息，但失败了

3 :  设置了timeout值，获取位置超时了

**数据收集** : options  (json的形式)

```js
 const options = {
    enableHighAccuracy: true,
    maximumAge: 1000,
    timeout: 10000,
}
```

enableHighAcuracy : 更精确的查找，默认false

timeout : 获取位置允许最长时间，默认infinity

maximumAge : 位置可以缓存的最大时间，默认0



### Canvas 画布

> HTML5 <canvas> 元素用于图形的绘制，通过javascript等脚本语言操作API实现绘制

#### 元素

> canvas看起来和 img元素很相像，唯一的不同就是它并没有 src 和 alt 属性。实际上， 标签只有两个属性 width和height。

```html
<canvas id="myCanvas" width="200" height="100">
    您的浏览器不支持canvas画布 请使用ie9+版本浏览器
</canvas>

```

#### 绘制直线

```js
//先获取画布
const canvas = document.querySelector('canvas');

//配置绘制的环境
const context = canvas.getContext('2d');

//在绘制之前，加上
context.beginPath(); // 意思是开始绘制

//设置起点 
context.moveTo(10,10); // 这里的第一个参数是x轴，第二个参数是y轴

//设置下一个点，
context.lineTo（x,y）; // 下个一个点坐标

//结束绘制
context.closePath();

//画线条
context.stroke() ;
```

### 方法

#### getContext()

> getContext方法返回canvas的绘制上下文, 通过上下文环境我们才可以进行绘制

基本上，只要我们使用canvas实现功能，getContext()方法调用100%需要使用。甚至可以这么说，只要你想用canvas实现任何平面效果，首先不管三七二十一，先把下面2行写上：

```js
const canvas = document.querySelector('canvas');
const context = canvas.getContext('2d');
// 2d是canvas最常用的绘制环境
```

#### toBlob()

> toBlob()方法可以Canvas图像对应的Blob对象（binary large object）。此方法可以把Canvas图像缓存在磁盘上，或者存储在内存中，这个往往由浏览器决定。

```js
canvas.toBlob(callback, mimeType, quality);
```

**参数**

```html
callbackFunction
	toBlob()方法执行成功后的回调方法，支持一个参数，表示当前转换的Blob对象。

mimeType（可选）String
	mimeType表示需要转换的图像的mimeType类型。默认值是image/png，还可以是image/jpeg，甚至image/webp（前提浏览器支持）等。

quality（可选）Number
	quality表示转换的图片质量。范围是0到1。由于Canvas的toBlob()方法转PNG是无损的，因此，此参数默认是没有效的，除非，指定图片mimeType是image/jpeg或者image/webp，此时默认压缩值是0.92。
```



#### toDataURL()

> Canvas本质上就是一个位图图像，因此，浏览器提供了若干API可以将Canvas图像转换成可以作为IMG呈现的数据，其中最老牌的方法就是`HTMLCanvasElement.toDataURL()`，此方法可以返回Canvas图像对应的data URI，也就是平常我们所说的base64地址



```js
canvas.toDataURL(mimeType, quality);
```

**参数**

```html
mimeType（可选）String
mimeType表示需要转换的图像的mimeType类型。默认值是image/png，还可以是image/jpeg，甚至image/webp（前提浏览器支持）等。
quality（可选）Number
quality表示转换的图片质量。范围是0到1。此参数要想有效，图片的mimeType需要是image/jpeg或者image/webp，其他mimeType值无效。默认压缩质量是0.92。
根据自己的肉眼分辨，如果使用toDataURL()的quality参数对图片进行压缩，同样的压缩百分比呈现效果要比Adobe Photoshop差一些。
。
```

**返回值**

> 返回base64 data图片数 据



### Context2D 上下文

> canvas的绘制API 属性和方法主要集中在 2D上下文中

```js
const canvas = document.querySelector('canvas');
const context = canvas.getContext('2d'); //Context2D
```

#### 属性

**canvas**

> 获取上下文的canvas对象

**fillStyle**

> 设置填充样式

```js
context.fillStyle = color; //使用纯色填充，支持RGB，HSL，RGBA，HSLA以及HEX色值。
context.fillStyle = gradient; //使用渐变填充，可以是线性渐变或者径向渐变。
context.fillStyle = pattern; //使用纹理填充。由于图片也能作为纹理，因此fillStyle也能填充普通的位图，可参见下面的案例。
```

**stockStyle**

> 设置描边样式

```js
 context.strokeStyle = 'red';
context.fillStyle = 'blue';
context.lineWidth = 10;
context.strokeRect(40, 20, 160, 80);
context.fillRect(40, 20, 160, 80);
```

![image-20200921192818626](assets/image-20200921192818626.png)

**font**

> 设置canvas中文本的字体字号 默认值: 10px sans-serif

```js
context.font = '24px SimSun, Songti SC';
```

**textAlign**

> 和CSS的`text-align`属性值类似，支持`left`，`right`，`centerstart`，`end`这些值，具体含义参见下面的语法。
>
> 其中`value`支持如下几个关键字：
>
> - left
>
>   文本左对齐。也就是最终绘制的文本内容最左侧位置就是设定的`x`坐标值。
>
> - right
>
>   文本右对齐。也就是最终绘制的文本内容最右侧位置就是设定的`x`坐标值。
>
> - center
>
>   文本居中对齐。也就是最终绘制的文本内容的水平中心位置就是设定的`x`坐标值。
>
> - start
>
>   文本起始方位对齐。如果文本是从左往右排列的，则表示左对齐；如果文本是从右往左排列的（例如设置`context.direction`为`rtl`），则表示右对齐。
>
> - end
>
>   文本结束方位对齐。如果文本是从左往右排列的，则表示右对齐；如果文本是从右往左排列的（例如设置`context.direction`为`rtl`），则表示左对齐。

**lineWidth**

>表示绘制的线条粗细 默认值 1.0

```js
context.lineWidth = value; //value 表示线的宽度。数值类型，默认值是1.0。如果是负数，0，NaN，或者Infinity都会忽略。
```

**shadowColor**

> 阴影颜色 HEX RGB RGBA

**shadowBlur**

> 阴影模糊度 默认值是`0`，表示不模糊。

**shadowOffsetX**

> 阴影X偏移

**shadowOffsetY** 

> 阴影Y偏移

```js
// 上阴影
context.shadowColor = 'rgb(50, 50, 50)';
context.shadowBlur = 5;
context.shadowOffsetY = -5;
// 文字80像素，黑体，红色
context.fillStyle = 'red';
context.font = '70px STheiti, simHei';
context.fillText('上偏移', 10, 88);
```

![image-20200921192413273](assets/image-20200921192413273.png)

**globalCompositeOperation**

> 混合模式  

```js
 ctx.globalCompositeOperation = model;
```

<a href="assets/globalCompositeOperation.html">模式详情</a>

#### 方法



**moveTo()**

> 绘制点移动到指定位置 通常表示起始点

```js
context.moveTo(x, y);
x Number 绘制的直线的落点的横坐标。
y Number 绘制的直线的落点的纵坐标。
```

**lineTo()**

> 直线连接当前最后子路径点与lineTo指定点

```js
context.lineTo(x, y); 
x Number 绘制的直线的落点的横坐标。
y Number 绘制的直线的落点的纵坐标。
```

**stroke()**

> 对路径进行描边

```js
context.stroke();
```

例: 


```js
context.moveTo(50, 20);
context.lineTo(200, 100);
context.stroke();
```

![image-20200921200455424](assets/image-20200921200455424.png)

**arc()**

> 绘制圆弧

```js
context.arc(x, y, radius, startAngle, endAngle [, anticlockwise]);

x  Number 圆弧对应的圆心横坐标。
y  Number圆弧对应的圆心纵坐标。
radius  Number圆弧的半径大小。
startAngle  Number圆弧开始的角度，单位是弧度。
endAngle  Number圆弧结束的角度，单位是弧度。
anticlockwise（可选）Boolean 弧度的开始到结束的绘制是按照顺时针来算，还是按时逆时针来算。如何设置为true，则表示按照逆时针方向从startAngle绘制到endAngle。

// 逆时针绘制0到1/4弧度圆弧
context.beginPath();
context.arc(150, 75, 50, 0, Math.PI / 2, true);
context.stroke();
```

![image-20200921194337510](assets/image-20200921194337510.png)

**arcTo()**

> 给路径添加圆弧，需要指定控制点和半径

```js
context.arcTo(x1, y1, x2, y2, radius);

x1 Number 第1个控制点的横坐标。
y1 Number 第1个控制点的纵坐标。
x2 Number 第2个控制点的横坐标。
y2 Number 第2个控制点的纵坐标。
radius Number 圆弧的半径大小。


context.beginPath();
context.moveTo(50, 50);
context.arcTo(150, 100, 200, 40, 40);
context.lineTo(200, 40);
context.stroke();
```

![image-20200921194318018](assets/image-20200921194318018.png)

**beginPath()**

> 绘制新路径

```js
context.beginPath(); 
```



**clearRect()**

> 擦除指定区域的画布内容 

```js
context.clearRect(x, y, width, height);
x Number 矩形左上角x坐标。
y Number 矩形左上角y坐标。
width Number 被清除的矩形区域的高度。
height Number 被清除的矩形区域的宽度度。
```

**clip()**

> 根据路径剪裁

```js
context.clip();
context.clip(fillRule);
context.clip(path, fillRule);

fillRule  String
填充规则。用来确定一个点实在路径内还是路径外。可选值包括：
nonzero：非零规则。此乃默认规则。
evenodd：奇偶规则。
关于'nonzero'和'evenodd'规则可参见这篇文章。

path  Object
指Path2D对象。
```

```js
var context = canvas.getContext('2d');
// 需要图片先加载完毕
var img = new Image();
img.onload = function () {
    // 剪裁路径是三角形
    context.beginPath();
    context.moveTo(20, 20);
    context.lineTo(200, 80);
    context.lineTo(110, 150);
    // 剪裁
    context.clip();
    // 填充图片
    context.drawImage(img, 0, 0, 250, 167);
};
img.src = './1.jpg';
```

![image-20200921194726131](assets/image-20200921194726131.png)

**closePath()**

> 闭合路径 连接起始点与结束点形成闭合区域

```js
context.closePath();
```

```js
// 绘制三角
context.beginPath();
context.moveTo(10, 10);
context.lineTo(140, 70);
context.lineTo(70, 140);
// 不执行闭合，直接描边
context.stroke();

// 绘制另外一个三角
context.beginPath();
context.moveTo(160, 10);
context.lineTo(290, 70);
context.lineTo(220, 140);
// 执行闭合，然后描边
context.closePath();
context.stroke();
```

![image-20200921194833213](assets/image-20200921194833213.png)

**createLinearGradient()**

> 创建线性渐变对象

```js

context.createLinearGradient(x0, y0, x1, y1);

x0 Number 渐变起始点横坐标。
y0 Number 渐变起始点纵坐标。
x1 Number 渐变结束点横坐标。
y1 Number 渐变结束点纵坐标。
线性渐变效果比较好脑补，就是从坐标点[x0, y0]到坐标点[x1, y1]的位置画一条线，然后整个渐变色带与与这条线垂直。
```

```js

var context = canvas.getContext('2d');
// 创建渐变
var gradient = context.createLinearGradient(0, 0, 300, 0);
gradient.addColorStop(0, 'red');
gradient.addColorStop(1, 'green');
// 设置填充样式为渐变
context.fillStyle = gradient;
// 左上角和右下角分别填充2个矩形
context.fillRect(10, 10, 160, 60);
context.fillRect(120, 80, 160, 60);
```

![image-20200921195123823](assets/image-20200921195123823.png)

**drawImage()**

> 绘制图片 用于实现图像压缩 水印添加 合成图像等操作

```js
context.drawImage(image, dx, dy);
context.drawImage(image, dx, dy, dWidth, dHeight);
context.drawImage(image, sx, sy, sWidth, sHeight, dx, dy, dWidth, dHeight);
```

```js
各个参数含义和作用如下：

image Object
绘制在Canvas上的元素，可以是各类Canvas图片资源（见CanvasImageSource），如<img>图片，SVG图像，Canvas元素本身等。
dx Number
在Canvas画布上规划一片区域用来放置图片，dx就是这片区域的左上角横坐标。
dy Number
在Canvas画布上规划一片区域用来放置图片，dy就是这片区域的左上角纵坐标。
dWidth Number
在Canvas画布上规划一片区域用来放置图片，dWidth就是这片区域的宽度。
dHeight Number
在Canvas画布上规划一片区域用来放置图片，dHeight就是这片区域的高度。
sx Number
表示图片元素绘制在Canvas画布上起始横坐标。
sy Number
表示图片元素绘制在Canvas画布上起始纵坐标。
sWidth Number
表示图片元素从坐标点开始算，多大的宽度内容绘制Canvas画布上。
sHeight Number
表示图片元素从坐标点开始算，多大的高度内容绘制Canvas画布上。

```

1. 第1类 就是image，同上，没什么好说的；
2. 第2类 就是dx，dy，dWidth和dHeight，表示在Canvas画布上划出一片区域用来放置图片，dx，dy为canvas元素的左上角坐标，dWidth，dHeight指Canvas元素上用在显示图片的区域大小。如果没有指定dx，dy，dWidth和dHeight这4个参数，则图片会被拉伸或缩放在这片区域内。
3. 第3类 就是sx，sy，sWidth和sHeight，你可以理解为对原始图片的提前剪裁。sx，sy表示图片上sx，sy这个坐标作为剪裁的左上角，sWidth和sHeight尺寸范围是最终剪裁出来的图片尺寸。sx，sy，sWidth和sHeight这4个参数就可以得到一个剪裁好的新图，然后我们把这个新图放在dx，dy，dWidth和dHeight这个Canvas画布区域中，就是最终的效果。另外，此处的所有坐标和宽高值都是相对于图片的原始尺寸而言的。
   drawImage()方法有一个非常怪异的地方，大家一定要注意，那就是5参数和9参数用法的参数位置是不一样的，这个和一般的API有所不同。一般API可选参数是放在后面。但是，这里的drawImage()使用9个参数时候，可选参数sx，sy，sWidth和sHeight是在前面的。如果不注意这一点，有些表现会让你无法理解。

**拉伸图片同时保持图片比例**

```js
//如何填满Canvas画布，同时保持图片的原始比例呢？这个就需要用到sx，sy，sWidth和sHeight这几个参数，注意，这4个参数是要写在dx，dy，dWidth和dHeight前面的，和一般的API不一样。

context.drawImage(image, 0, 42, 500, 250, 0, 0, 300, 150);
```

![image-20200921195459851](assets/image-20200921195459851.png)

**fill()**

> 填充路径

```js
context.fill();
context.fill(fillRule);
context.fill(path, fillRule);


fillRule String
填充规则。用来确定一个点实在路径内还是路径外。可选值包括：
nonzero：非零规则，此乃默认规则。
evenodd：奇偶规则。
关于'nonzero'和'evenodd'规则可参见这篇文章。

path Object
指Path2D对象。
```

```js
context.beginPath();
context.arc(60, 60, 40, 0, Math.PI * 2);
context.fillStyle = '#368';
context.fill();
```

![image-20200921195933207](assets/image-20200921195933207.png)

**rect()**

> 绘制矩形路径

```js
context.rect(x, y, width, height);

x Number 矩形路径的起点横坐标。
y Number 矩形路径的起点纵坐标。
width Number 矩形的宽度。
height Number 矩形的高度。
```

```js
context.rect(100, 25, 100, 100);
context.stroke();
```

![image-20200921201240884](assets/image-20200921201240884.png)



**strokeRect()**

> 矩形描边 其他图形没有的现成填充方法

```js
context.strokeRect(x, y, width, height);

x Number 矩形路径的起点横坐标。
y Number 矩形路径的起点纵坐标。
width Number 矩形的宽度。
height Number 矩形的高度。
```

```js
context.lineWidth = 2;
context.strokeRect(75, 25, 150, 100);
```

![image-20200921201424693](assets/image-20200921201424693.png)

**fillRect()**

> 图形填充(矩形) 其他图形没有的现成填充方法

```js
context.fillRect(x, y, width, height);

x Number 填充矩形的起点横坐标。
y Number 填充矩形的起点纵坐标。
width Number 填充矩形的宽度。
height Number 填充矩形的高度。
```

```js
// 中心点坐标
let centerX = canvas.width / 2;
let centerY = canvas.height / 2;
// 矩形填充
context.fillRect(centerX - 30, centerY - 4, 60, 8);
context.fillRect(centerX - 4, centerY - 30, 8, 60);
```

![image-20200921200132436](assets/image-20200921200132436.png)

**save() & restore()**

> save存储状态  restore还原状态 
>
> save()保存当前Canvas画布状态并放在栈的最上面，可以使用restore()方法依次取出。 

```js

// 保存初始Canvas状态
context.save();
// 设置红色填充
context.fillStyle = 'red';
// 矩形填充
context.fillRect(20, 20, 100, 60);
// 还原在绘制
context.restore();
// 矩形填充again
context.fillRect(180, 60, 100, 60);
```

![image-20200921201009311](assets/image-20200921201009311.png)

**fillText()**

> 用来填充文字，是Canvas绘制文本的主力方法。

```js
context.fillText(text, x, y [, maxWidth]);

text String 用来填充的文本信息。
x Number 填充文本的起点横坐标。
y Number 填充文本的起点纵坐标。
maxWidth（可选）Number 填充文本占据的最大宽度 超过此宽度的时候文本会压缩 不会换行
```



```js
context.font = '24px STheiti, SimHei';
context.wrapText('Canvas H5画布', 24, 56, 200);
```



**measureText()**

> 用来测量文本的一些数据，返回TextMetrics对象，包含字符宽度等信息。

```js
context.measureText(text);

text String 被测量的文本。
```

```js
// 设置字体字号
context.font = '24px STHeiTi, SimHei';
// 文本信息对象就有了
var textZh = context.measureText('帅');
var textEn = context.measureText('handsome');
// 文字绘制
context.fillText('帅', 60, 50);
context.fillText('handsome', 60, 90);
// 显示宽度
context.font = '12px Arial';
context.fillStyle = 'red';
context.fillText('宽' + textZh.width, 62 + textZh.width, 40);
context.fillText('宽' + textEn.width, 62 + textEn.width, 80);
```

![image-20200922184637391](assets/image-20200922184637391.png)





**scale()**

> 来缩放Canvas画布的坐标系，只是影响坐标系，之后的绘制会受此方法影响，但之前已经绘制好的效果不会有任何变化。

```js
context.scale(x, y);

x Number
Canvas坐标系水平缩放的比例。支持小数.
y Number
Canvas坐标系垂直缩放的比例。支持小数.
```

```js
// 显示绘制个正方形用来对比
context.fillRect(10, 10, 10, 10);
// 缩放
context.scale(10, 3);
// 再次绘制
context.fillRect(10, 10, 10, 10);

// 恢复坐标系
context.setTransform(1, 0, 0, 1, 0, 0);

```

![image-20200922182450274](assets/image-20200922182450274.png)

```js
// 记住Canvas状态
context.save();
// 来来来，垂直翻转下
context.scale(1, -1);
// 填充文字
context.font = '32px STHeiti, SimHei';
context.fillText('换个角度看世界', 36, -64);
// 恢复状态，不要影响接下来的绘制
context.restore();
```

![image-20200922182506710](assets/image-20200922182506710.png)

**rotate()**

> 添加旋转 顺时针方向 单位弧度 
>
> 默认旋转中心点是Canvas的左上角(0, 0)坐标点，如果希望改变旋转中心点，例如以Canvas画布的中心旋转，需要先使用translate()位移旋转中心点。
>
> 角度转弧度计算公式是：radian = degree * Math.PI / 180。例如，旋转45°，旋转弧度就是45 * Math.PI / 180。

```js
context.rotate(angle);

angle Number
Canvas画布坐标系旋转的角度，单位是弧度。注意，此旋转和CSS3的旋转变换不一样，旋转的是坐标系，而非元素。因此，实际开发的时候，旋转完毕，需要将坐标系再还原。
```

![Canvas旋转示意图](assets/explain-1600770649159.png)

```js
// 旋转45度
context.rotate(45 * Math.PI / 180);
// 字体填充
context.font = '20px STHeiti, SimHei';
context.fillText('旋转，跳跃，我闭着眼', 60, -40, 188);
// 重置当前的变换矩阵为初始态
context.setTransform(1, 0, 0, 1, 0, 0);

```

![image-20200922183218079](assets/image-20200922183218079.png)



**transform()**

> 方法对Canvas坐标系进行整体移动, 用于改变其他变化方式的变换中心

```js
context.translate(x, y);
x Number 坐标系水平位移的距离。
y Number 坐标系垂直位移的距离。
```

![Canvas位移示意图](assets/explain.png)

黑色为原始坐标系，红色为移动后的坐标系。


```js
var img = new Image();
img.onload = function () {
    var context = canvas.getContext('2d');
    // 坐标位移
    context.translate(150, 100);
    // 旋转45度
    context.rotate(45 * Math.PI / 180);
    // 再位移回来
    context.translate(-150, -100);
    // 此时绘制图片就是中心旋转了
    context.drawImage(this, 0, 0, 300, 200);

    // 坐标系还原
    context.setTransform(1, 0, 0, 1, 0, 0);
};
img.src = './1.jpg';

```

![image-20200922182920363](assets/image-20200922182920363.png)

**setTransform()**

> 方法通过矩阵变换重置当前坐标系
>
> 此方法和transform()方法的区别在于，后者不会完全重置已有的变换，而是累加。

```js
context.setTransform(a, b, c, d, e, f);

a Number 水平缩放。
b Number 水平斜切。
c Number 垂直斜切。
d Number 垂直缩放。
e Number 水平位移。
f Number 垂直位移。
```

```js
//还原坐标系

context.translate(150, 100);
// 旋转45度
context.rotate(45 * Math.PI / 180);
// 再位移回来
context.translate(-150, -100);
// 此时绘制图片就是中心旋转了
context.drawImage(this, 0, 0, 300, 200);

// 坐标系还原 100100
context.setTransform(1, 0, 0, 1, 0, 0);
```



**createImageData()**

> 方法可以创建一个全新的空的ImageData对象。该对象中的所有像素信息都是透明黑。

```js
context.createImageData(width, height); 
context.createImageData(imagedata);

返回值是ImageData对象，包含width，height和data这3个只读属性。参数具体含义如下：

width Number
ImageData对象包含的width值。如果ImageData对象转换成图像，则此width也是最终图像呈现的宽度。
height Number
ImageData对象包含的height值。如果ImageData对象转换成图像，则此height也是最终图像呈现的高度。
imagedata Object
一个存在的ImageData对象，只会使用该ImageData对象中的width和height值，包含的像素信息会全部转换为透明黑。
```



**getImageData()**

> 方法可以根据参数获取画布上对应位置的图像对象

```js
ImageData = ctx.getImageData(sx, sy, sw, sh);

参数
sx 要被提取的图像数据矩形区域的左上角 x 坐标。
sy 将要被提取的图像数据矩形区域的左上角 y 坐标。
sw 将要被提取的图像数据矩形区域的宽度。
sh 将要被提取的图像数据矩形区域的高度。

返回值
一个ImageData 对象，包含canvas给定的矩形图像数据。

错误抛出
IndexSizeError
如果高度或者宽度变量为0，则抛出错误。
```



**putImageData()**

> 将数据从已有的 ImageData对象绘制到位图的方法

```js
ctx.putImageData(imagedata, dx, dy);
ctx.putImageData(imagedata, dx, dy, dirtyX, dirtyY, dirtyWidth, dirtyHeight);

参数
imageData
	ImageData ，包含像素值的数组对象。
dx
	源图像数据在目标画布中的位置偏移量（x 轴方向的偏移量）。
dy
	源图像数据在目标画布中的位置偏移量（y 轴方向的偏移量）。
dirtyX 可选
	在源图像数据中，矩形区域左上角的位置。默认是整个图像数据的左上角（x 坐标）。
dirtyY 可选
	在源图像数据中，矩形区域左上角的位置。默认是整个图像数据的左上角（y 坐标）。
dirtyWidth 可选
	在源图像数据中，矩形区域的宽度。默认是图像数据的宽度。
dirtyHeight 可选
	在源图像数据中，矩形区域的高度。默认是图像数据的高度。


```



### requestAnimationFrame 帧动画

> **`window.requestAnimationFrame()`** 告诉浏览器——你希望执行一个动画，并且要求浏览器在下次重绘之前调用指定的回调函数更新动画。该方法需要传入一个回调函数作为参数，该回调函数会在浏览器下一次重绘之前执行

```js
window.requestAnimationFrame(callback);
```

#### 参数

`callback`

下一次重绘之前更新动画帧所调用的函数(即上面所说的回调函数)。该回调函数会被传入[`DOMHighResTimeStamp`](https://developer.mozilla.org/zh-CN/docs/Web/API/DOMHighResTimeStamp)参数，该参数与[`performance.now()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Performance/now)的返回值相同，它表示`requestAnimationFrame()` 开始去执行回调函数的时刻。

#### 返回值

一个 `long` 整数，请求 ID ，是回调列表中唯一的标识。是个非零值，没别的意义。你可以传这个值给 [`window.cancelAnimationFrame()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Window/cancelAnimationFrame) 以取消回调函数。



requestAnimationFrame还有以下两个优势：

- **CPU节能**：使用setTimeout实现的动画，当页面被隐藏或最小化时，setTimeout 仍然在后台执行动画任务，由于此时页面处于不可见或不可用状态，刷新动画是没有意义的，完全是浪费CPU资源。而requestAnimationFrame则完全不同，当页面处理未激活的状态下，该页面的屏幕刷新任务也会被系统暂停，因此跟着系统步伐走的requestAnimationFrame也会停止渲染，当页面被激活时，动画就从上次停留的地方继续执行，有效节省了CPU开销。

- **函数节流**：在高频率事件(resize,scroll等)中，为了防止在一个刷新间隔内发生多次函数执行，使用requestAnimationFrame可保证每个刷新间隔内，函数只被执行一次，这样既能保证流畅性，也能更好的节省函数执行的开销。一个刷新间隔内函数执行多次时没有意义的，因为显示器每16.7ms刷新一次，多次绘制并不会在屏幕上体现出来。

#### 针节流

```js
var locked = false;
window.addEventListenser('scroll',function(){
    if(!locked){
        locked = true;
        window.requestAnimationFrame(fAnim);
    }
});

function fAnim(){
    locked = false;
    //code
}
```



#### 兼容封装

```js
if (!Date.now)

    Date.now = function() { return new Date().getTime(); };

(function() {

    'use strict';

    var vendors = ['webkit', 'moz'];

    for (var i = 0; i < vendors.length && !window.requestAnimationFrame; ++i) {

        var vp = vendors[i];

        window.requestAnimationFrame = window[vp+'RequestAnimationFrame'];

        window.cancelAnimationFrame = (window[vp+'CancelAnimationFrame']

                                   || window[vp+'CancelRequestAnimationFrame']);

    }

    if (/iP(ad|hone|od).*OS 6/.test(window.navigator.userAgent) // iOS6 is buggy

        || !window.requestAnimationFrame || !window.cancelAnimationFrame) {

        var lastTime = 0;

        window.requestAnimationFrame = function(callback) {

            var now = Date.now();

            var nextTime = Math.max(lastTime + 16, now);

            return setTimeout(function() { callback(lastTime = nextTime); },

                              nextTime - now);

        };
        window.cancelAnimationFrame = clearTimeout;
    }

}());
```

### worker 多线程

> JavaScript 语言采用的是单线程模型，也就是说，所有任务只能在一个线程上完成，一次只能做一件事。前面的任务没做完，后面的任务只能等着。随着电脑计算能力的增强，尤其是多核 CPU 的出现，单线程带来很大的不便，无法充分发挥计算机的计算能力。
>
> Web Worker 的作用，就是为 JavaScript 创造多线程环境，允许主线程创建 Worker 线程，将一些任务分配给后者运行。在主线程运行的同时，Worker 线程在后台运行，两者互不干扰。等到 Worker 线程完成计算任务，再把结果返回给主线程。这样的好处是，一些计算密集型或高延迟的任务，被 Worker 线程负担了，主线程（通常负责 UI 交互）就会很流畅，不会被阻塞或拖慢。
>
> Worker 线程一旦新建成功，就会始终运行，不会被主线程上的活动（比如用户点击按钮、提交表单）打断。这样有利于随时响应主线程的通信。但是，这也造成了 Worker 比较耗费资源，不应该过度使用，而且一旦使用完毕，就应该关闭。



#### Web Worker 限制

（1）**同源限制**

分配给 Worker 线程运行的脚本文件，必须与主线程的脚本文件同源。

（2）**DOM 限制**

Worker 线程所在的全局对象，与主线程不一样，无法读取主线程所在网页的 DOM 对象，也无法使用`document`、`window`、`parent`这些对象。但是，Worker 线程可以`navigator`对象和`location`对象。

（3）**通信联系**

Worker 线程和主线程不在同一个上下文环境，它们不能直接通信，必须通过消息完成。

（4）**脚本限制**

Worker 线程不能执行`alert()`方法和`confirm()`方法，但可以使用 XMLHttpRequest 对象发出 AJAX 请求。

（5）**文件限制**

Worker 线程无法读取本地文件，即不能打开本机的文件系统（`file://`），它所加载的脚本，必须来自网络。



#### 写法

```js
let worker = new Worker('worker.js');

创建一个专用Web worker，它只执行URL指定的脚本。使用 Blob URL 作为参数亦可。
```

`Worker()`构造函数，可以接受两个参数。第一个参数是脚本的网址（必须遵守同源政策），该参数是必需的，且只能加载 JS 脚本，否则会报错。第二个参数是配置对象，该对象可选。它的一个作用就是指定 Worker 的名称，用来区分多个 Worker 线程。

`Worker()`构造函数返回一个 Worker 线程对象，用来供主线程操作 Worker。Worker 线程对象的属性和方法如下。

#### 属性和方法

```js
Worker.onerror：指定 error 事件的监听函数。
Worker.onmessage：指定 message 事件的监听函数，发送过来的数据在Event.data属性中。
Worker.onmessageerror：指定 messageerror 事件的监听函数。发送的数据无法序列化成字符串时，会触发这个事件。
Worker.postMessage()：向 Worker 线程发送消息。
Worker.terminate()：立即终止 Worker 线程。
```

####  Worker 线程

Web Worker 有自己的全局对象，不是主线程的`window`，而是一个专门为 Worker 定制的全局对象。因此定义在`window`上面的对象和方法不是全部都可以使用。

Worker 线程有一些自己的全局属性和方法。

> - self.name： Worker 的名字。该属性只读，由构造函数指定。
> - self.onmessage：指定`message`事件的监听函数。
> - self.onmessageerror：指定 messageerror 事件的监听函数。发送的数据无法序列化成字符串时，会触发这个事件。
> - self.close()：关闭 Worker 线程。
> - self.postMessage()：向产生这个 Worker 线程发送消息。
> - self.importScripts()：加载 JS 脚本。



#### 用例

主线程采用`new`命令，调用`Worker()`构造函数，新建一个 Worker 线程。

> ```javascript
> var worker = new Worker('work.js');
> ```

`Worker()`构造函数的参数是一个脚本文件，该文件就是 Worker 线程所要执行的任务。由于 Worker 不能读取本地文件，所以这个脚本必须来自网络。如果下载没有成功（比如404错误），Worker 就会默默地失败。

然后，主线程调用`worker.postMessage()`方法，向 Worker 发消息。

> ```javascript
> worker.postMessage('Hello World');
> worker.postMessage({method: 'echo', args: ['Work']});
> ```

`worker.postMessage()`方法的参数，就是主线程传给 Worker 的数据。它可以是各种数据类型，包括二进制数据。

接着，主线程通过`worker.onmessage`指定监听函数，接收子线程发回来的消息。

> ```javascript
> worker.onmessage = function (event) {
>   console.log('Received message ' + event.data);
>   doSomething();
> }
> 
> function doSomething() {
>   // 执行任务
>   worker.postMessage('Work done!');
> }
> ```

上面代码中，事件对象的`data`属性可以获取 Worker 发来的数据。

Worker 完成任务以后，主线程就可以把它关掉。

> ```javascript
> worker.terminate();
> ```

####  

#### Worker 线程文件

Worker 线程内部需要有一个监听函数，监听`message`事件。

> ```javascript
> self.addEventListener('message', function (e) {
>   self.postMessage('You said: ' + e.data);
> }, false);
> ```

上面代码中，`self`代表子线程自身，即子线程的全局对象。因此，等同于下面两种写法。

> ```javascript
> // 写法一
> this.addEventListener('message', function (e) {
>   this.postMessage('You said: ' + e.data);
> }, false);
> 
> // 写法二
> addEventListener('message', function (e) {
>   postMessage('You said: ' + e.data);
> }, false);
> ```

除了使用`self.addEventListener()`指定监听函数，也可以使用`self.onmessage`指定。监听函数的参数是一个事件对象，它的`data`属性包含主线程发来的数据。`self.postMessage()`方法用来向主线程发送消息。

根据主线程发来的数据，Worker 线程可以调用不同的方法，下面是一个例子。

> ```javascript
> self.addEventListener('message', function (e) {
>   var data = e.data;
>   switch (data.cmd) {
>     case 'start':
>       self.postMessage('WORKER STARTED: ' + data.msg);
>       break;
>     case 'stop':
>       self.postMessage('WORKER STOPPED: ' + data.msg);
>       self.close(); // Terminates the worker.
>       break;
>     default:
>       self.postMessage('Unknown command: ' + data.msg);
>   };
> }, false);
> ```

上面代码中，`self.close()`用于在 Worker 内部关闭自身。

#### Worker 加载脚本

Worker 内部如果要加载其他脚本，有一个专门的方法`importScripts()`。

> ```javascript
> importScripts('script1.js');
> ```

该方法可以同时加载多个脚本。

> ```javascript
> importScripts('script1.js', 'script2.js');
> ```

####  错误处理

主线程可以监听 Worker 是否发生错误。如果发生错误，Worker 会触发主线程的`error`事件。

> ```javascript
> worker.onerror(function (event) {
>   console.log([
>     'ERROR: Line ', e.lineno, ' in ', e.filename, ': ', e.message
>   ].join(''));
> });
> 
> // 或者
> worker.addEventListener('error', function (event) {
>   // ...
> });
> ```

Worker 内部也可以监听`error`事件。



#### 关闭 Worker

使用完毕，为了节省系统资源，必须关闭 Worker。

> ```javascript
> // 主线程
> worker.terminate();
> 
> // Worker 线程
> self.close();
> ```



#### 同页面的 Web Worker

通常情况下，Worker 载入的是一个单独的 JavaScript 脚本文件，但是也可以载入与主线程在同一个网页的代码。

> ```html
> <!DOCTYPE html>
>   <body>
>     <script id="worker" type="app/worker">
>       addEventListener('message', function () {
>         postMessage('some message');
>       }, false);
>     </script>
>   </body>
> </html>
> ```

上面是一段嵌入网页的脚本，注意必须指定``标签的`type`属性是一个浏览器不认识的值，上例是`app/worker`。

然后，读取这一段嵌入页面的脚本，用 Worker 来处理。

> ```javascript
> var blob = new Blob([document.querySelector('#worker').textContent]);
> var url = window.URL.createObjectURL(blob);
> var worker = new Worker(url);
> 
> worker.onmessage = function (e) {
>   // e.data === 'some message'
> };
> 
> ----------------------------------------
> function createWorker(f) {
>     var blob = new Blob(['(' + f.toString() + ')()']);
>     var url = window.URL.createObjectURL(blob);
>     var worker = new Worker(url);
>     return worker;
> }
> ```

上面代码中，先将嵌入网页的脚本代码，转成一个二进制对象，然后为这个二进制对象生成 URL，再让 Worker 加载这个 URL。这样就做到了，主线程和 Worker 的代码都在同一个网页上面。n

### Notifications

**通知**接口用于向用户配置和显示桌面通知。



```html
let notification = new Notification(title, options)
```

#### 参数

- `title`

  一定会被显示的通知标题

- `options` 可选

  一个被允许用来设置通知的对象。它包含以下属性：

  `dir` : 文字的方向；它的值可以是 `auto（自动）`, `ltr（从左到右）`, or `rtl`（从右到左）

  `lang`: 指定通知中所使用的语言。这个字符串必须在 [BCP 47 language tag](http://tools.ietf.org/html/bcp47) 文档中是有效的。

  `body`: 通知中额外显示的字符串`tag`: 赋予通知一个ID，以便在必要的时候对通知进行刷新、替换或移除。

  `icon`: 一个图片的URL，将被用于显示通知的图标。

#### 静态属性

这些属性仅在 `Notification` 对象上有效。

- [`Notification.permission`](https://developer.mozilla.org/zh-CN/docs/Web/API/Notification/permission) 只读

  一个用于表明当前通知显示授权状态的字符串。可能的值包括：`denied` (用户拒绝了通知的显示), `granted` (用户允许了通知的显示), 或 `default` (因为不知道用户的选择，所以浏览器的行为与 denied 时相同).

#### 方法

#### 静态方法

这些方法仅在 `Notification` 对象中有效。

- [`Notification.requestPermission()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Notification/requestPermission)

  用于当前页面向用户申请显示通知的权限。这个方法只能被用户行为调用（比如：onclick 事件），并且不能被其他的方式调用。

#### 实例方法

这些方法仅在 `Notification` 实例或其 [`prototype`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Inheritance_and_the_prototype_chain) 中有效。

- [`Notification.close()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Notification/close)

  用于关闭通知。

#### 案例

```js
  const request = document.querySelector('#request-role');
  const sendMsg = document.querySelector('#send-msg');

  request.onclick = function () {
      //发起通知权限请求
      Notification.requestPermission()
  }
  sendMsg.onclick = function () {
      let notif = new Notification('海牙的通知', { lan: 'zh-CN', body: '你好,我是海牙,你中了500w大奖,请来欢乐豆大厅兑换', icon: 'images/bird.png' });
      
      notif.onshow = function () {
        console.log('通知')
      }
      
      notif.onclick = function () {
        console.log('用户点击了通知');
      }

      notif.onclose = function () {
        console.log('用户关闭了通知')
      }

    }
```

