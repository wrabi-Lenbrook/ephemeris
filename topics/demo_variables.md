---
dates: 1757, 1764, 1767, 1780, 1790, 1799, 1857
title: Demo page for variables
---

# {{ page.title }}

Print the dates on a list:

{% for item in page.dates %}

- {{ item }}

{% endfor %}
