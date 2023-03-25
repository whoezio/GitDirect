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