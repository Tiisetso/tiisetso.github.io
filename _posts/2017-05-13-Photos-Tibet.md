---
layout:     post
title:      Tibet 西藏
date:       2017-05-12 16:31:19
summary:    Photo highlights from my six days in Tibet, China.
categories: china
---
<ul style="list-style: none;">
{% for image in site.static_files %}
    {% if image.path contains 'posts/Tibet' %}
        <li><img src="{{ site.url }}{{ image.path }}" /></li>
    {% endif %}
{% endfor %}
</ul>
