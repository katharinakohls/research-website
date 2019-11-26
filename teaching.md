---
title: Teaching
layout: default
order: 3
---

<title>{{ page.title }} | {{ site.title }}</title>

<ul>
    {% for link in site.data.navigation %}
    <li><a href="{{ link.url }}">{{ link.title }}</a></li>
    {% endfor %}
</ul>
