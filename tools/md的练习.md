####关于强调
**粗体**
*斜体*

__粗体__
_斜体_

*这个呢
会换行*

##关于分割线
---
呵呵哒

##引用
<blockquote>这里是引用</blockquote>
呵呵
>这里是引用
>>引用中的引用哦！





##关于标题：SetText方式
大标题
===
小标题
---

##无序列表
符号之后的空格不能少，-+*效果一样，但不能混合使用，因混合是嵌套列表，内容可超长
- 无序列表
- 无序列表
- 无序列表：我很长。我也很长！那比一比啊？比就比！我有这么长，你有我长吗？我有这么这么长！好吧，你赢了！

+ 无序列表
+ 无序列表

* 无序列表
 + 子无序列表
 + 子无序列表
* 无序列表

##有序列表
数字不能省略但可无序，点号之后的空格不能少
1. 有序列表
2. 有序列表
3. 有序列表
8. 有序列表


##嵌套列表
-+*可循环使用，但符号之后的空格不能少，符号之前的空格也不能少

##文字超链接
Tooltips可省略
[不如](http://bruce-sha.github.io"不如的博客")

##图片超链接
多个感叹号，Tooltips可省略，要设置大小只能借助HTML标记
![Github Mark](http://github.global.ssl.fastly.net/images/moudles/logos_page/GitHub-Mark.png "GitHub Mark")

##索引超链：Reference方式
索引，1 2可以是任意字符

[不如][1]
![GitHub Octocat][2]
[1]:http://bruce-sha.github.io "tooltips"
[2]:http://github.global.sll.fastly.net/images/modules/logos_page/Octocat.png

##自动连接
尖括号
<http://ibruce.info>
<curtainwang@qq.com>

##代码：行内代码
+ 在第一行后指定编程语言，也可以不指定
<!--0-->
val s="hello markdown"
println(s)

##代码：段落代码
+ 每行文字前加4个空格或者这一个Tab

    val s="hello markdown"
    println(s)
    
    val s="hello markdown"
    println(s)
    
    
##代码：hexo
+ 可以制定编程语言，
『% codeblock [title] [lang:language] [url] [link text] %』
  code snippet
『% endcodeblock %』


##注释
+ 用html的注释

##转义字符
+ 用html的转义字符
+ Markdown中的转义字符为\，转义的有：
  * 反斜杠 \\
  * 反引号 \`
  * 星号 \*
  * 下划线 \_
  * 大括号 \{\}
  * 小括号 \(\)
  * 井号 \#
  * 加号 \+
  * 减号 \-
  * 英文句号 \.
  * 感叹号 \!
  

##其他
+ 文本中可直接用html标签，但是要前后加上空行