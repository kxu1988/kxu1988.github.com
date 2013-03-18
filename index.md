---
layout: page
title: 许可不可以
tagline: 生命中最大的失去不是死亡，而是人活着时候心里的怅然若失
---
{% include JB/setup %} 

##最近文章

-----

{% for category in site.categories %} 
  <h3 id="{{ category[0] }}-ref">{{ category[0] | join: "/" }}</h3>
  <ul>
    {% assign pages_list = category[1] %}  
    {% include JB/pages_list %}
  </ul>
{% endfor %}
