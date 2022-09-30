---
permalink: /_/tmp/sitemap.html
---

<ul>
{% for item in site.pages %}
    <li><a href="{{ item.permalink }}">{{ item.title | default: site.title | default: site.github.repository_name }}</a></li>
{% endfor %}
</ul>