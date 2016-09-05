---
layout: default
---

```liquid
{% assign {{sort_pages}} = site.pages | sort:"url" %}
{{sort_pages}}
```

output: 

{% assign sort_pages = site.pages | sort:"url" %}
{{sort_pages}}
