---
layout:     post
title:      North Korea 朝鲜
date:       2017-04-03 21:24:00
summary:    Photo highlights from a brief trip to North Korea.
categories: china
---

{% for image in site.static_files %}
    {% if image.path contains 'posts/2017-04-03-North-Korea-Photos' %}
        <div>
          <img src="{{ site.url }}{{ image.path }}" />
        </div>
    {% endif %}
{% endfor %}
