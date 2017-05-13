---
layout:     post
title:      Tibet
date:       2017-05-13 16:31:19
summary:    Six days in Tibet.
categories: china
---


{% for image in site.static_files %}
    {% if image.path contains 'posts/Tibet' %}
        <img src="{{ site.baseurl }}{{ image.path }}" alt="Photos from Tibet" />
    {% endif %}
{% endfor %}
