---
layout: page
title: 许可不可以
tagline: 生命中最大的失去不是死亡，而是人活着时候心里的怅然若失
---
{% include JB/setup %} 

<ul class="posts">
  {% for post in site.posts %}
    {% if forloop.first %}
        <h3><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h3>
        {{ post.content | only_first_p}}
        <br>
        {{ post.date | date_to_string}}
        <hr />
        <h3>文章列表 / Post List</h3>
    {% else %}   
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li> 
    {% endif %}
  {% endfor %}
</ul>
