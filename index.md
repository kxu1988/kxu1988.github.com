---
layout: page
title: 许可不可以
tagline: 何时想念，何时再见
---
{% include JB/setup %}

###关于作者 / About Me 

*有多难就有多勇敢*

许可（Aaron），除了名字好像关于自己的一切都很苍白呀。

希望自己的简介能慢慢丰富起来。

这里主要聚合一些自己感兴趣的内容， 喜欢的电影、音乐，研究的技术，好玩的地方...


	请赐予我力量，去接受我所不能改变的；
	请赐予我勇气，去改变我所能改变的；
	并赐予我智慧去分辨两者的不同。 

--------------

> 关注我 / Follow Me

* [新浪微博](http://weibo.com/kxu14)
* [Facebook]() | [LinkedIn]() | [Twitter]()
* [GitHub](https://github.com/kxu1988)

>联系我 / Contact Me

* Email: <kxu@pku.edu.cn>
* Gtalk: <kxu1988@gmail.com>
* 
------

###文章列表 / Post List

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




