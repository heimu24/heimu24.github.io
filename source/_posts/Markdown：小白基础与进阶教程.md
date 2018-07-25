
---
title: 小白小白详细基础入门以及进阶教程
date: 2018-07-25 11:04:08
tags:
---

>#小白详细基础入门以及进阶教程
[toc]
#一、斜体、粗体

<font color=blue size=4>Markdown语法	</font>
	
	**双是粗体**
	__星号和下划线效果一样__
	*单个是斜体*
	_单个是斜体_
	**可以      加空格**

<font color=blue size=4>效果如下：</font>

**双是粗体**
__星号和下划线效果一样__
*单个是斜体*
_单个是斜体_
**可以      加空格**


---
#二、分割线

三个或者以上的-_*，必须单独一行，可含有空格。

<font color=blue size=4>Markdown语法	</font>


	---
	___
	***

<font color=blue size=4>效果如下	</font>

---
___
***

#三、区块引用

使用'>'角括号进行区块引用

<font color=blue size=4>Markdown语法	</font>
	
	>区块引用
	>>多层引用
<font color=blue size=4>效果如下	</font>

>区块引用
>>多层引用

---

#四、标题样式

markdown支持两种标题语法，Setext和atx，Setext 形式是用底线的形式，利用三个或更多 = （最高阶标题）和 - （第二阶标题），Atx 形式在行首插入 1 到 6 个 # ，对应到标题 1 到 6 阶。

<font color=blue size=4>Markdown语法	</font>

	Setext最高阶标题
	===
	Setext第二阶标题
	---
	#Atx一级标题
	##Atx二级标题
	###Atx三级标题
	####Atx四级标题
	####Atx五级标题
	#####Atx六级标题

<font color=blue size=4>效果如下	</font>

![为了目录好看，这里用了照片](https://img-blog.csdn.net/20180724200806902?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2hlaW11MjQ=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

---

#五、无序列表


使用-+*号，效果一样，注意符号后面的空格，但是不能混合使用，混合的话就成了嵌套列表

<font color=blue size=4>Markdown语法	</font>

	- 减号无序列表
	- 减号无序列表
	+ 加号无语列表
	+ 加号无序列表
	* 星号无序列表
	* 星号无序列表
	- - 混合使用
	+ + 混合使用
	+ * 混合使用
	* - 混合使用
<font color=blue size=4>效果如下	</font>

- 减号无序列表
- 减号无序列表
+ 加号无语列表
+ 加号无序列表
* 星号无序列表
* 星号无序列表
- - 混合使用
+ + 混合使用
+ * 混合使用
* - 混合使用

---
#六、有序列表

使用数字和英文句点，数字可以无序，注意点后面的空格

<font color=blue size=4>Markdown语法	</font>

	1. 有序列表1
	2. 有序列表2
	5. 有序列表5
	8. 有序列表8
	6. 有序列表6
<font color=blue size=4>效果如下	</font>

1. 有序列表1
2. 有序列表2
5. 有序列表5
8. 有序列表8
6. 有序列表6

---
#七、嵌套列表

注意第二级的前后都有空格

<font color=blue size=4>Markdown语法	</font>

	- 嵌套列表1
		 - 嵌套列表2
		 - 嵌套列表3
		  - 嵌套列表4
		    -  嵌套列表5

<font color=blue size=4>效果如下	</font>
- 嵌套列表1
 - 嵌套列表2
 - 嵌套列表3
  - 嵌套列表4
    -  嵌套列表5

---
#八、链接
链接有两种，行内(inline) 和 参考(reference)两种形式

##1、行内(inline)形式
行内形式是直接在后面用括号直接接上链接

<font color=blue size=4>Markdown语法	</font>

	[百度](www.baidu.com)

<font color=blue size=4>效果如下	</font>


[百度](www.baidu.com)


##2、加上title属性
也可以加上title属性，注意中间有个空格，使用双引号，把鼠标放在链接上，就可以看出区别了

<font color=blue size=4>Markdown语法	</font>

	[百度](www.baidu.com "with a title")

<font color=blue size=4>效果如下	</font>

[百度](www.baidu.com "with a title")

##3、参考(reference)方式：

<font color=blue size=4>Markdown语法	</font>

	这是[Google][1] ，这是[Yahoo][2]，这是[MSN][3].
	[1]: http://google.com/ "Google"
	[2]: http://search.yahoo.com/ "Yahoo Search"
	[3]: http://search.msn.com/ "MSN Search"

<font color=blue size=4>效果如下	</font>

这是[Google][1] ，这是[Yahoo][2]，这是[MSN][3].

[1]: http://google.com/ "Google"
[2]: http://search.yahoo.com/ "Yahoo Search"
[3]: http://search.msn.com/ "MSN Search"


##3、自动链接：自动链接直接用一对尖括号包围即可
<font color=blue size=4>Markdown语法	</font>

	<https://www.baidu.com>

<font color=blue size=4>效果	</font>
<https://www.baidu.com>

---
#九、插入图片：

图片的语法和文字链接的形式很像，只不过前面加个!，后面跟图片的地址

##1、行内(inline)形式
(注意title属性是可选的)

<font color=blue size=4>Markdown语法	</font>

	![kobe](http://pic11.photophoto.cn/20090626/0036036341009653_b.jpg "Kobe Bryant")

<font color=blue size=4>效果如下	</font>

![kobe](http://pic11.photophoto.cn/20090626/0036036341009653_b.jpg "Kobe Bryant")

##2、参考(reference)形式

效果和上面一样

<font color=blue size=4>Markdown语法	</font>

	![kobe][id]
	[id]:http://pic11.photophoto.cn/20090626/0036036341009653_b.jpg "Kobe Bryant"

---

#十、代码

##1、代码段
代码段在一般的段落文字中，你可以使用反引号 ` 来标记代码区段，区段内的 &、< 和 > 都会被自动的转换成 HTML 实体，这项特性让你可以很容易的在代码区段内插入 HTML 码：

<font color=blue size=4>Markdown语法	</font>

	I strongly recommend against using any `<blink>` tags.
	I wish SmartyPants used named entities like `&mdash;`
	instead of decimal-encoded entites like `&#8212;`
<font color=blue size=4>效果如下</font>

I strongly recommend against using any `<blink>` tags.
I wish SmartyPants used named entities like `&mdash;`
instead of decimal-encoded entites like `&#8212;`.

##2、段落代码块
如果要建立一个已经格式化好的代码区块，只要每行都<table><tr><td bgcolor=black><font color=red size=4>缩进 4 个空格或是一个 tab</font></td></tr></table> 就可以了，而 &、< 和 > 也一样会自动转成 HTML 实体。

<font color=blue size=4>效果如下	</font>

	我是代码块
	我是代码块
	我是代码块

##3、行内代码：高亮

在第一行的后面指定编程语言，也可以不指定。（Markdown目前好像不支持更改代码块背景颜色。。。。）

<font color=blue size=4>Markdown语法	</font>

	```  python
	@requires_authorization
	def somefunc(param1='', param2=0):
	    '''A docstring'''
	    if param1 > param2: # interesting
	        print 'Greater'
	    return (param2 - param1 + 1) or None
	class SomeClass:
	    pass
	>>> message = '''interpreter
	... prompt'''
	
	```


<font color=blue size=4>效果如下	</font>
```  python
@requires_authorization
def somefunc(param1='', param2=0):
    '''A docstring'''
    if param1 > param2: # interesting
        print 'Greater'
    return (param2 - param1 + 1) or None
class SomeClass:
    pass
>>> message = '''interpreter
... prompt'''

```

---
#十一、注释和html的一样
	
	<!-- 注释 -->


---
#十二、转义字符

<font color=blue size=4>Markdown语法	</font>

	\\ 反斜杠
	\` 反引号
	\* 星号
	\_ 下划线
	\{\} 大括号
	\[\] 中括号
	\(\) 小括号
	\# 井号
	\+ 加号
	\- 减号
	\. 英文句号
	\! 感叹号
<font color=blue size=4>效果如下	</font>


\\ 反斜杠
\` 反引号
\* 星号
\_ 下划线
\{\} 大括号
\[\] 中括号
\(\) 小括号
\# 井号
\+ 加号
\- 减号
\. 英文句号
\! 感叹号


---
#十三、表格


<font color=blue size=4>Markdown语法	</font>

	| name          | age           | sex   |
	| ------------- | ------------- | ------|
	| kobe          | 8             |  man  |
	| bryant        | 24			|  man  |

<font color=blue size=4>效果如下	</font>

| name          | age           | sex   |
| ------------- | ------------- | ------|
| kobe          | 8             |  man  |
| bryant        | 24			|  man  |

<font color=blue size=4>Markdown语法	</font>

	name	|	age
	---		|	---
	kobe	|	8
	bryant	|	24
<font color=blue size=4>效果如下	</font>
name	|	age
---		|	---
kobe	|	8
bryant	|	24



---

#<table><tr><td bgcolor=green><font color=red size=5>进阶教程<font>：</td></tr></table>

##1、更改字体、字号、颜色

Markdown 通过简单标记语法，使普通文本内容具有一定格式。但它本身不支持修改字体、字号与颜色等功能的。CSDN-markdown 编辑器是其衍生版本，支持基于 PageDown ( Stack Overflow）所使用的编辑器的扩展功能（如表格、脚注、内嵌HTML、内嵌 LaTeX 等等）。
Size：规定文本的尺寸大小，取值从 1 到 7 ，浏览器默认值是 3.

<font color=blue size=4>Markdown语法	</font>

	<font face="黑体">我是黑体字</font>
	<font face="微软雅黑">我是微软雅黑</font>
	<font face="STCAIYUN">我是华文彩云</font>
	<font color=red>我是红色</font>
	<font color=#008000>我是绿色</font>
	<font color=Blue>我是蓝色</font>
	<font size=5>我是尺寸</font>
	<font face="黑体" color=green size=5>我是黑体，绿色，尺寸为5</font>
<font color=blue size=4>效果如下	</font>

<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font face="STCAIYUN">我是华文彩云</font>
<font color=red>我是红色</font>
<font color=#008000>我是绿色</font>
<font color=Blue>我是蓝色</font>
<font size=5>我是尺寸</font>
<font face="黑体" color=green size=5>我是黑体，绿色，尺寸为5</font>

---
##2、为文字添加背景色

由于 style 标签和标签的 style 属性不被支持，所以这里只能是借助 table, tr, td 等表格标签的 bgcolor 属性来实现背景色。故这里对于文字背景色的设置，只是将那一整行看作一个表格，更改了那个格子的背景色（bgcolor）

<font color=blue size=4>Markdown语法	</font>

	<table><tr><td bgcolor=yellow>背景色yellow</td></tr></table>
<font color=blue size=4>效果如下	</font>

<table><tr><td bgcolor=yellow>背景色yellow</td></tr></table>

##3、设置图片大小
<font color=blue size=4>Markdown语法：更改图片百分比	</font>

	<img src="http://pic11.photophoto.cn/20090626/0036036341009653_b.jpg" width="50%" height="50%">
<font color=blue size=4>效果如下</font>

<img src="http://pic11.photophoto.cn/20090626/0036036341009653_b.jpg" width="50%" height="50%">

<font color=blue size=4>Markdown语法：更改图片像素值	</font>

	<img src="http://pic11.photophoto.cn/20090626/0036036341009653_b.jpg" width="251" height="350" >

<font color=blue size=4>效果如下	</font>

<img src="http://pic11.photophoto.cn/20090626/0036036341009653_b.jpg" width="251" height="350" >


<font color=blue size=4>Markdown语法：图片居中	</font>

	<div align=center><img src="http://pic11.photophoto.cn/20090626/0036036341009653_b.jpg" width="50%" height="50%"></div>

<font color=blue size=4>效果如下	</font>

<div align=center><img src="http://pic11.photophoto.cn/20090626/0036036341009653_b.jpg" width="50%" height="50%"></div>

ps：right、left

	基础知识：
	[TOC]                 #生成目录
	&#160;或者&nbsp;      #空格

---

#参考链接

[<font color=Coral size=5>RGB颜色对照表</font>](https://blog.csdn.net/heimu24/article/details/81192697)

[<font color=BlueViolet size=5 >Markdown 语法大全 包括设置字体 颜色](https://blog.csdn.net/qcx321/article/details/53780672)

[<font color=GreenYellow size=5>Markdown: Basics （快速入门）</font>](https://www.appinn.com/markdown/basic.html)

[<font color=LightSeaGreen size=5>CSDN-markdown 文字样式设置（字体, 大小, 颜色, 高亮底色）</font>](https://blog.csdn.net/thither_shore/article/details/52181464)