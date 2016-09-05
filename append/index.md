---
layout: default
---

{% assign x = 'abc' %}
{% assign y = 'def' %}
{% assign z = x | append: ' - ' | append: y %}
{{ z }}
