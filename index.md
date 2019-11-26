---
title: Katharina Kohls, PhD
layout: default
order: 1
---

<title>{{ page.title }} | {{ site.title }}</title>

Markdown **content** for the website.

<ul>
    {% for link in site.data.navigation %}
    <li><a href="{{ link.url }}">{{ link.title }}</a></li>
    {% endfor %}
</ul>


<ul>
  {% assign mypages = site.pages | sort: "order" %}
    {% for page in mypages %}
    <li><a href="{{ page.url | absolute_url }}">{{ page.title }}</a></li>
    {% endfor %}
  </ul>
