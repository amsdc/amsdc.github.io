---
permalink: /_/tmp/sitemap.html
---

{% for item in site.pages %}
    {{ item.permalink }}
{% endfor %}
