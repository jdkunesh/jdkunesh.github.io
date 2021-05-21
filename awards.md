---
title: Awards
published: true

---

<ul>

{% for item in site.data.awards %}

<li><a href="{{ item.url }}">{{ item.title }}</a>
    <p>{{ item.organization }} {{ item.year }}</p>
</li>


{% endfor %}
</ul>

