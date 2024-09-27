---
layout: page
title: Templates
---

{% for page in site.pages %}
{% for cat in page.categories %}
{% if cat == "templates" %}
- <a href="{{ page.url }}">{{ page.title }}</a>
{% endif %}
{% endfor %}
{% endfor %}
