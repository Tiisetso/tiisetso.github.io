---
layout:     post
title:      North Korea 朝鲜
date:       2017-04-03 21:24:00
summary:    Photo highlights from a brief trip to Sinuiju, North Korea.
categories: china
---
<ul style="list-style: none;">
{% for image in site.static_files %}
    {% if image.path contains 'posts/2017-04-03-North-Korea-Photos' %}
        <li><img src="{{ site.url }}{{ image.path }}" /></li>
    {% endif %}
{% endfor %}
</ul>
