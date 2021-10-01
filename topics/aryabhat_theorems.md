---
layout: template_generalFiles
title: Aryabhat’s theorems
---

# {{page.title}}

Space, as defined by the Oxford English dictionary, is the dimensions of height, depth, and width within which all things exist and move. It is almost a vacuum, containing almost nothing. This _nothingness_ has been described poetically by several books, like you can see here: lala


{% for item in site.data.origin %}

-  {{ item.book }}: {{ item.extract }}

{% endfor %}

We know from observations that space is filled with objects that are, primarily, spherical in nature and are hot dense masses of solids, liquids, and gas, and that these spherical masses might have sentient life forms living on them.

One such mass is known as Earth and is populated, inter alia, by human beings. One such human being, who lived a very long time ago, was known as Aryabhat. He was a mathematician and an astronomer who formulated the following theorems.

<table>
<tr>
<th>Theorem name</th><th>Theorem text</th>
</tr>
{% for item in site.data.theorems %}
<tr><td>{{ item.name }}</td><td>{{ item.text }}</td></tr>
{% endfor %}
</table>

## See also

-  [Time and distance](time_distance.md)
-  [Planets and stars](planet_stars.md)

