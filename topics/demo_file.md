---
layout: demo
title: Rising Sun
---

# {{ page.title }}

An investigation into storms and other natural phenomena.

Show the time: {{ site.when }}

Data file contents:

{% for item in site.data.demo %}

The country of {{ item.name }} was created in {{ item.date }}. Its flag is {{ item.flag }}.

{% endfor %}