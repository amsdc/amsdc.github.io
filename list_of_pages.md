---
permalink: /_sitemap.private
---

{% for item in site.pages %}
    {{ item.permalink }}
{% endfor %}
