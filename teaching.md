---
title: Teaching
layout: default
order: 3
---

<title>{{ page.title }} | {{ site.title }}</title>

<ul class="nav-ul">
    {% for link in site.data.navigation %}
    <li class="nav-li"><a href="{{ link.url }}">{{ link.title }}</a></li>
    {% endfor %}
</ul>
