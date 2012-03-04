---
layout: name
title: Home

section: Home
---

<img class='inset right' src='/files/images/wish.png' title='Mr.Wi$h' width='120px' />

欢迎
=======

爱网络，爱潜水。爱工作，爱奋斗。爱学习，也爱钻研。我擅长技术，崇尚简单的快乐和幸福。我不是什么电脑高手，我是技术宅。我和你一样，为了未来在奋斗。

+--	{.section}
个人信息
========
昵称：		 Mr.Wi$h
=--
+-- {.section}
性别：			  男
=--
+-- {.section}
民族：			汉族
=--
+-- {.section}
学历：			大专
=--
+-- {.section}
出日：	  1988.10.29
=--
+-- {.section}
籍贯：	内蒙古包头市
=--
+-- {.section}
现居住地：	  天津市

=--

+-- {.section}
求职意向
=====
网络/系统管理员、安防弱电、web开发方向

=--

+-- {.section}
工作性质
=====
全职（可出差）

=--

+-- {.section}
工作经历
=====
{% for post in site.categories.iem limit:3 %}
<ul class="compact recent">
<li>
	<a href="{{ post.url }}" title="{{ post.excerpt }}">{{ post.title }}</a>
	<span class="date">{{ post.date | date_to_string }}</span> 
</li>
</ul>
{% endfor %}
=--

+--{.section}
座右铭
======
在人之上时，要视别人为人；在人之下时，要视自己为人。
=--

+-- {.section}
[Email](#)
====================================

huanghunjzl@163.com

=--

+-- {.section}
