---
title: Press
published: false

---

<ul>

{% for item in site.data.press %}

<li><a href="{{ item.url }}">{{ item.title }} - {{ item.organization }}</a>, {{ item.year }}</li>


{% endfor %}
</ul>

