---
layout: page
title: 许可不可以
tagline: 生命中最大的失去不是死亡，而是人活着时候心里的怅然若失
---
{% include JB/setup %} 

###文章列表 / Post List

<ul class="posts">
  {% for post in site.posts %}
    <h3>{{ forloop.first.title }}</h3>
    {{ forloop.first.content | 100}}
    {{ forloop.first.date | date_to_string}}
    <hr />
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
