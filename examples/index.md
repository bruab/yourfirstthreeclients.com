---
layout: page
title: Examples
---

{% for page in site.pages %}
{% for cat in page.categories %}
{% if cat == "examples" %}
- <a href="{{ page.url }}">{{ page.title }}</a>
{% endif %}
{% endfor %}
{% endfor %}
