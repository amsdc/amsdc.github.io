---
permalink: /sitemap
title: Sitemap
---



<ul>
{% for item in site.pages %}
    <li><a href="{{ item.permalink }}">{{ item.title | default: item.permalink}}</a></li>
{% endfor %}
</ul>