---
layout: page
title: 许可不可以
tagline: 生命中最大的失去不是死亡，而是人活着时候心里的怅然若失
---
{% include JB/setup %} 

<ul class="posts">
  {% for post in site.posts %}
    
        {{ post | only_first_p }}
       
  {% endfor %}
</ul>
