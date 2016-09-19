---
layout: default
---


{% for repository in site.github.public_repositories %}
* [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}

{% for repository in site.github.public_repositories %}
{{ repository.html_url }}
{% endfor %}
