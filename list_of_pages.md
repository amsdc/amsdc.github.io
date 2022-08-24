---
permalink: /_/tmp/sitemap
---

{% for item in site.pages %}
    {{ item.permalink }}
{% endfor %}
