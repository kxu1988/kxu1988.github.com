---
layout: page
title: 许可不可以
tagline: 生命中最大的失去不是死亡，而是人活着时候心里的怅然若失
---
{% include JB/setup %} 

<ul class="posts">
  {% for post in site.posts %}
    {% if forloop.first %}
        <h3>{{ post.title }}</h3>
        {{ post.content | 100}}
        <br>
        {{ post.date | date_to_string}}
        <hr />
        <h3>文章列表 / Post List</h3>
    {% elseif %}   
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li> 
    {% endif %}
  {% endfor %}
</ul>
