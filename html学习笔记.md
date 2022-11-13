# HTML学习笔记:sparkles:
## 组成部分
* 文档的声明代码  
`<!DOCTYPE>`声明正确才能正确的显示网页。  
:bulb:tips:`<!DOCTYPE>`不区分大小写  
* 页面代码  
页面代码部分又由**头部元素**和**可视化页面**两部分内容组成，我们在网页上的能看到的只有**可视化页面代码**部分的内容。
## 属性  
属性在html元素中以名称和值对的形式出现  
如：`charset="UTF-8"`  
多个属性用空格隔开。  
## 元素
即为html**开始标签**和**结束标签**  
标签：由**尖括号**包围的关键词。  
* **头部标签**`<head>`
在头部标签中使用`<titile>`标签来作为文档的标题。  
![效果图](https://upload-images.jianshu.io/upload_images/28672505-049242f74fef47a4.png?imageMogr2/auto-orient/strip|imageView2/2/w/660/format/webp)   
在`<head>`标签里，可以通过`<mata>`标签的charset属性来规定文档使用哪种字符编码。  
`<mata charset="UTF-8">`基本包含了全世界所有国家需要使用的所有字符。  
若未写charset属性则会出现乱码.
* **标题**`<h1></h1>`  
最多有六级标题。  
* **段落**`<p></p>`  
* **body标签**  
`<body></body>`  
* **html标签**  
`<html></html>`  
结合使用
```
<html>

<body>
<p>段落</p>
</body>

</html>
```  
* **链接**  
`<a href="https://github.com/0919teriri/Tasks.git"></a>`  
还可以添加target属性来设置目标窗口弹开的方式。  
`target="_self"`为当前页面打开
`target="_blank"`为在新窗口打开  
* **图像**  
`<img src="路径" />`   
还可以添加  
alt图片显示不出则以文字显示  
titile鼠标放在图片上显示的文字  
以及width height border 来设置图片的宽度高度和边框粗细。  
* **换行**`<br/>`  
* **文字格式化标签**  
```
<strong>加粗</strong>
<del>删除线</del>
<em>斜体</em>
<ins>下划线</ins>
```    
![效果图](https://upload-images.jianshu.io/upload_images/28672505-ad7a10635c28d0a9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  
* **布局标签**  
`<div>`标签为块级元素。一行只能有一个div  
`<span>`标签为行级元素。可以有多个span  
```
    <div>区块1</div><div>区块2</div>
    <span>区块3</span><span>区块4</span>
```    
![效果图](https://upload-images.jianshu.io/upload_images/28672505-93b4e18a425b6363.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  
* **注释标签**  
`<!--注释语句-->`或者ctrl加/的快捷方式  
* **表格标签**  
`<table>`定义一个表格  
`<tr>`定义表格中的行必须嵌套在table中    
`<td>`定义单元格必须嵌套在tr中  
`<th>`定义表头单元格，表头内文字加粗并居中  
用`<thead>`和`<tbody>`来分割表格的头部和主体区域。  
表格的属性  
align left center right 来定义对齐方式  
border 1或" " 来表示是否有边框  
width 像素值或者百分比 定义表格的宽度    
* **表单标签**  
用`<form>`来定义表单。  
`<input>`为输入标签，在input标签内输入type属性来定义输入类型  
`type="text"`为文本域  
`type="password"`为密码字段以*代替  
`type="radio"`为单选按钮   
`type="checkbox"`为多选按钮  
`type="submit"`为提交按钮，提交至action属性定义的服务端  
`type="reset"`为重置表单内容  
`type="button"`为创建一个点击按钮   
`type="file"`为文件域  
`<lebel>`标签来将文本与表单元素绑定，点击文本时自动将光标转到对应的表单元素上  
`<select>`定义下拉表单元素标签  
在select标签里用`<option>`来定义下拉列表的选项内容  
`<textarea>`定义多行文本域  
用cols和rows属性来定义每行的字数和显示的行数  
可以在type属性后用value属性来自定义按钮的文本  
:bulb:tips:  
:one:虽然`<p>` `<br>`等格式也被接受，但是最好还是加上结束标签。  
:two:html标签虽然不区分大小写但是，更推荐使用小写来写标签。  



