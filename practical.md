---
layout: page
title: Practicals
---

<!-- technology ideas, computers, etc. -->

<!-- add links pointing to markdown files in the folder "practicals" -->
{% for page in site.pages %}
{% if page.path contains 'practicals' %}
  [{{ page.title }}]({{ page.url }})
{% endif %}
{% endfor %}
