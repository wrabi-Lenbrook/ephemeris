---
layout: demo
title: Rising Sun
---

# {{ page.title }}

An investigation into storms.

{% for item in site.data.flags %}
The country of {{ item.name }} was created in {{ item.date }}. Its flag is {{ item.flag }}.
{% endfor %}

