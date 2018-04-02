---
title: "Sample Page"
permalink: /sample-page/
layout: single
<!--collection: recipes-->
---

luka
{% for image in site.static_files %}
    {% if image.path contains 'docs/assets/images' %}
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}
