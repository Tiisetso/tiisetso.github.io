---
layout:     post
title:      Tibet 西藏
date:       2017-05-12 16:31:19
summary:    Six days in Tibet.
categories: china
---

<img src="{{ site.url }}/assets/posts/Tibet/DSCF2574.jpg" />

{% for image in site.static_files %}
    {% if image.path contains 'posts/Tibet' %}
        <img src="{{ site.url }}{{ image.path }}" />
    {% endif %}
{% endfor %}

{% for image in site.static_files %}
    {% if image.path contains 'img' %}
        <img src="{{ site.url }}{{ image.path }}" />
    {% endif %}
{% endfor %}
