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