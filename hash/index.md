---
layout: default
---

{% for link_hash in page.links %}
  {% for link in link_hash %}
    <a href="{{ link[1] }}">{{ link[0] }}</a>
  {% endfor %}
{% endfor %}
