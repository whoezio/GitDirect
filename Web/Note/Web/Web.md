# HTML
## HTML元素
### 1. 元素是指从开始标签到结束标签的所有代码
### 2. 元素语法
- 元素的内容是从开始标签与结束标签之间的内容
- 空元素在开始标签中进行关闭
- 大多数HTML元素可拥有属性
### 3. 嵌套的HTML元素
- 大多数的HTML元素都可以嵌套
## HTML属性
### 1. 标签可以拥有属性为元素提供更多信息
### 2. 属性以键/值对的形式出现
如: href="www.bilibilli.com"
### 3.常用标签属性
- `<h1> : align对其方式`
- `<body> : bgcolor背景颜色`
- `<a> : target规定在何处打开链接`
### 4. 通用属性:
- class : 规定元素的类名
- id : 规定元素唯一ID
- style : 规定元素样式
- title : 规定元素的额外信息
## HTM格式化
| 标签     | 描述 |
|------    |:----|
|`<b>`     |<b>定义粗体文字</b>      |
|`<big>`   |<big>定义大号字</big>      |
|`<em>`    |<em>定义着重文字</em>      |
|`<i>`     |<i>定义斜体字</i>        |
|`<small>` |<small>定义小号字</small>      |
|`<strong>`|<strong>定义加重语气</strong>    |
|`<sub>`   |下标<sub>定义下标字</sub>     |
|`<sup>`   |上标<sup>定义上标字</sub>      |
|`<ins>`   |<ins>定义插入字</ins>      |
|`<del>`   |<del>定义删除字</del>       |
## HTML样式
### 1. 标签
- `<style>` : 样式定义
- `<link>` : 资源引用
### 2. 属性
- rel = "stylesheet" : 外部样式表
- type = "text/css" : 引入文档的类型
- margin-left : 边距
### 3. 属性
1. 三种样式表插入方法
	>外部样式表:
		
		<link rel = "stylesheet" type = "text/css" href = "mystyle.css">
	>内部样式表:

		<style type = "text/css">
		body{background-color : red}
		p{margin-left : 20px}
		</style>
	>内联样式表:

		<p style = "color : red">
## HTML链接
### 1. 链接数据:
- 文本链接
- 图片链接
### 2.属性:
- href属性 : 指向另一个文档的链接
- name属性 : 创建文档内的链接
### 3.img标签属性:
- alt : 替换文本属性
- width : 宽
- height : 高
## HTML表格
<table border = "2">
	<caption>表格标题</caption>
	<tr>
		<th>表格</th>
		<th>描述</th>
	</tr>
	<tr>
		<td>&lttable&gt</td>
		<td>定义表格</td>
	</tr>
	<tr>
		<td>&ltcaption&gt</td>
		<td>定义表格标题</td>
	</tr>
	<tr>
		<td>&ltth&gt</td>
		<td>定义表格的表头</td>
	</tr>
	<tr>
		<td>&lttr&gt</td>
		<td>定义表格的行</td>
	</tr>
	<tr>
		<td>&lttd&gt</td>
		<td>定义表格的单元</td>
	</tr>
	<tr>
		<td>&ltthead&gt</td>
		<td>定义表格的页眉</td>
	</tr>
	<tr>
		<td>&lttbody&gt</td>
		<td>定义表格的主体</td>
	</tr>
	<tr>
		<td>&lttfoot&gt</td>
		<td>定义表格的页脚</td>
	</tr>
	<tr>
		<td>&ltcol&gt</td>
		<td>定义表格的列属性</td>
	</tr>
</table>

### 表格的定义
- 表格内的标签

		<tr>
			<td>
				<ul>
					<li>列表1</li>
					<li>列表2</li>
				</ul>
			</td>
			<td>表格内的标签</td>
		</tr>

<p align = center>
	<img src = "Source\表格内的标签.png"><br/>
	<i>表格内标签显示效果</i>
 </p>

- 单元格的边距 : cellpadding

		<table cellpadding = "10">

- 单元格的间距 ：cellspaceing
  
		<table cellspacing = "10">

- 表格的背景图片 : background

		<table background = "path">

- 单元格内容排列
- 跨行和跨列单元格
## HTML列表
<table border = "2" width = "500px" bgcolor = "cadetblue">
	<caption>HTML列表</caption>
	<tr bgcolor = "darkseagreen">
		<th>标签</th>
		<th>描述</th>
	</tr>
	<tr>
		<td>&ltol&gt</td>
		<td>有序列表</td>
	</tr>
	<tr>
		<td>&ltul&gt</td>
		<td>无序列表</td>
	</tr>
	<tr>
		<td>&ltli&gt</td>
		<td>列表项</td>
	</tr>
	<tr>
		<td>&ltdl&gt</td>
		<td>列表</td>
	</tr>
	<tr>
		<td>&ltdt&gt</td>
		<td>列表项</td>
	</tr>
	<tr>
		<td>&ltdd&gt</td>
		<td>描述</td>
	</tr>
</table>

### 1. 无序列表
- 使用标签 : `<ul>`, `<li>`
- 属性 : disc, circle, square
### 2. 有序列表
- 使用标签 : `<ol>`, `<li>`
- 属性 : A, a, l, i, start
### 3. 嵌套列表
- 使用标签 : `<ul>`, `<ol>`, `<li>`
### 4. 自定义列表
- 使用标签: : `<dl>`, `<dt>`, `<dd>`
### 5. 使用属性

		<标签 type = 属性>

## HTML块
### 1. HTML块元素
- 块元素在显示时, 通常会以新行开始
- 如 : `<h1>`, `<p>`, `<ul>`
### 2. HTML内联元素
- 内联元素通常不会以新行开始
- 如 : `<b>`, `<a>`, `<img>`
### 3. HTML`<div>`元素
- `<div>`元素也被称为块元素, 其主要是组合HTML元素的容器
### 4. HTML`<span>`元素
- `<span>`元素是内联元素, 可作为文本的容器

## HTML布局
### 1. 使用div元素布局
### 2. 使用table布局

## HTML表单和php环境搭建
### 1. 表单的创建
1. 表单用于获取不同类型的用户输入
2. 常用表单标签
<table width="500px" bgcolor="cadetblue">
	<tr bgcolor="coral">
		<th>标签</th>
		<th>描述</th>
	</tr>
	<tr>
		<td>&ltform&gt</td>
		<td>表单</td>
	</tr>
	<tr>
		<td>&ltinput&gt</td>
		<td>输入域</td>
	</tr>
	<tr>
		<td>&lttextarea&gt</td>
		<td>文本域</td>
	</tr>
	<tr>
		<td>&ltlable&gt</td>
		<td>控制标签</td>
	</tr>
	<tr>
		<td>&ltfieldset&gt</td>
		<td>定义域</td>
	</tr>
	<tr>
		<td>&ltlegend&gt</td>
		<td>域的标题</td>
	</tr>
	<tr>
		<td>&ltselect&gt</td>
		<td>选择的列表</td>
	</tr>
	<tr>
		<td>&ltoptgroup&gt</td>
		<td>选项组</td>
	</tr>
	<tr>
		<td>&ltoption&gt</td>
		<td>下拉列表中的选项</td>
	</tr>
	<tr>
		<td>&ltbutton&gt</td>
		<td>按钮</td>
	</tr>
</table>

### 3.input域控件
1. 复选框

		<input type="checkbox">

2. 单选按钮
   
		<td>男<input type="radio" name="sex"></td>
		<td>女<input type="radio" name="sex"></td>

3. 下拉列表
   
		<select name="web" id="select1">
			<option value="www.baidu.com">www.baidu.com</option>
			<option value="www.bing.com">www.bing.com</option>
			<option value="www.google.com">www.google.com</option>
		</select>

4. 文本域

		<textarea name="test" id="text1" cols="30" rows="10">说点什么吧...</textarea>

5. 创建按钮
   
		<input type="button" value="按钮">

## HTML框架
### 1. 框架标签(frame):
- 框架对于页面的设计有着很大的作用
### 2. 框架集标签(`<frameset>`):
- 框架集标签定义如何将窗口分割为框架
- 每一个frameset定义一系列行或列
- rows/cols的值规定了每行或每列的面积
### 3. 常用标签
- noresize : 固定框架大小
- cols : 列
- rows : 行
### 4. 内联框架
- iframe

		<iframe src="frame1.html" frameborder="0" margin="0px" width="800px" height="800px"></iframe>

## HTML背景
### 1. 背景标签
- background
### 2. 背景颜色
- bgcolor
### 3. 颜色
- 颜色是由一个十六进制符号来定义,这个符号由RGB值组成
## HTML实体
### 1. 实体:
- HTML中预留字符串必须被替换成字符实体<br>如:<,>,&

# HTML_XHTML
### 1. 什么是XHTML
- 可扩展超文本标记语言
- 与HTML4.01几乎相同
- 更严格更纯净的HTML版本
- 是以XML应用的方式定义的HTML
- 得到所有主流浏览器的支持
### 2. 为什么使用XHTML
- 为了代码的完整性和良好性
### 3. 文档声明
- DTD : 规定了使用通用标记语言的网页语法<br>STRICT(严格类型)<br>TRANSITIONAL(过渡类型)<br>FRAMESET(框架类型) 

## XHTML的元素
### 1. XHTML元素语法
- 必须正确嵌套
- 必须始终关闭
- 必须小写
- 必须有一个根元素

## XHTML属性
### 1. XHTML属性语法规则
- 必须使用小写
- 必须使用双引号包裹
- 禁止最小化

# HTML5和HTML4的区别
## 推出的理由及目标
HTML5的出现，对于Web来说意义是非常重大的，因为他的意图是想要把目前Web上存在的各种问题一并解决掉了。
- Web浏览器之间的兼容性很低
- 文档结构不够明确
- Web应用程序的功能受到了限制

世界知名浏览器厂商对HTML5的支持
微软、Google、苹果、Opera、Mozilla


