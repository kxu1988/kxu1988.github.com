---
layout: post
title: "不必要的折腾，关于jekyll-only_first_p插件"
description: ""
category: 
tags: []
---
{% include JB/setup %}

习惯了“标题 + 第一段摘要 + Read More”， 所以也想在Github上搭建的博客首页也实现这个效果。

Google了一下，找到了Jekyll-only_first_p这个插件，折腾了几个小时，本地输出的页面是我希望的，但Commit到Github上，输出的页面就是不对。
最后终于发现问题所在

    "Plugins are disabled during deployment to github pages"
    https://github.com/mojombo/jekyll/issues/325
                    
原来Github出于安全考虑，禁用了Jekyll的插件。

失望之余，便想寻找其它方法。但转念一想，我真的需要实现这个效果吗？

一篇文章，标题没有吸引力，用户还会看你的摘要吗？
一篇文章确实是用户的兴趣所在，他是点开全文详细阅读、还是看完题目再看摘要再点开看全文呢？

所以，我个人认为，最需要的就是题目尽量提供完整的信息，避免让用户再猜测文章是否值得阅读上面浪费时间。

利人利己！