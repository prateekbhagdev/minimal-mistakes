---
title: "Sample Page"
permalink: /sample-page/
layout: collection
collection: recipes
---

luka
{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  {{ myimage.path }}
{% endfor %}
