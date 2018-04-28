#2018百度前端技术学院 基础学院 学习笔记（一)

##笔记该怎么写：
1.学习目标，是否达成，学习总用时
2.哪些东西了解的比较透彻，谈谈理解
3.哪些东西了解到了一些，还有哪些点需要后续继续深入阅读
4.哪些东西学了之后还有很多疑惑没有被解答，记录问题，以待后续解决

##课程目标：

什么是web ，什么是HTML,CSS,JavaScript

##总用时：3小时

了解透彻的：

###1.What is web？

        web 包括了web客户端、web服务端，采用常见的(B/S)计算机结构，中间可有通信协议，如http,https 
web简单的工作原理：web客户端 通过URL网址链接 提交请求到web服务端申请拿取数据，web服务端响应请求，根据其要求找到相应的数据并返回数据给客户端(双方买卖的过程)
web客户端是啥？常见的浏览器咯，web服务器又是啥？ 一台24小时工作的电脑(嘻嘻,取个独特的名字增强神秘感)保存有页面啊~,数据等，相对浏览器而言。什么？就是那些网页早就弄好了，
如果你要，你就发送请求给我，我发给你。(简单介绍)
那么

###2.What is HTML ?
        Html(Hypertext Markup Language) 超文本标记语言，主要用在web中，是搭建起web网页的结构，嗯……，就是相当于人体的骨架嘛(确实没啥美观，可人家实用啊)
Html和普通的编程语言的区别(Html不是真正的编程语言)，不是一路人~~
Html 中的几个关键词 元素(elements),标签(tags),内容(content),属性(Attribute).
接下来解析以下几个与html相关的关键词：
{
Html是由一系列元素(elements)组成的。
元素(elements)是由 标签(tags)+内容(content)组成的。
元素(elements)这个家伙还有属性(Attribute)，放在开始标签(tags)中
属性(Attribute)带有属性值(就像家属一样)
}
有了基本的Html的组成认识，现在来看下Html页面的基本结构

        {
            <!DOCTYPE html>
            <html>
              <head>
                <meta charset="utf-8">
                <title>My test page</title>
              </head>
              <body>
                <img src="images/firefox-icon.png" alt="My test image">
              </body>
            </html>
        }
        <!DOCTYPE html> — 文档类型（doctypes）,必须带上(规则嘛~)
        <html>根元素,包含整个页面的内容
        <head> 元素,常可用于引用css样式(后面讲)、字符编码等,用户不可见的(好像挺神秘的)
        <meta charset="utf-8"> 文档所使用的字符编码
        <title></title> 页面的标题，显示在浏览器标签上(网页被收藏为标签的默认名称)
        
###3.What is CSS ?
CSS(Cascading Style
Sheets)层叠样式表，样式表达语言(非真正编程语言);有啥用？纯html文档太丑了，不符合我们人类的审美观，所以得弄些画面好看的样式放上去，
css就是干这活的(即是为Html文档添加你想要的样子的一种表达式)。既是美化HTML文档的东西，得有些规矩吧(不能乱改乱涂呢，咱又不是小学生~)。

下面来看CSS规则：

p{
    color:red;
}
p:     选择符(Selector)
color:red   :声明(Declaration)
color: 属性(Property)
red  : 属性值(Property Value)
大括号里面放除选择符外的声明
冒号分离属性和属性值
分号分离每个声明

往下扩展可有选择符的扩展、声明的扩展等
CSS 有一个重要的东西叫做盒子模型

###4.What is JavaScript?
        javascript 跟Java没有半毛钱关系一个编程语言，应用于HTML文档，可以在网站上提供动态交互。
展开的话就很多东西要讲了，反正现在记住它是提供网页交互的就是了嘛。
