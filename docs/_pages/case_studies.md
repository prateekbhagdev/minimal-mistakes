---
title: Case studies
layout: collection
permalink: /case_studies/
author_profile: true
collection: portfolio
entries_layout: grid
classes: wide
---

Sample document listing for the collection `_portfolio`.

<div class="grid__wrapper">
  {% for post in site.portfolio %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
