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