---
title: Events
published: false

---

<ul>
{% for item in site.data.events %}
{% if item.live %} 
    <li>{{ item.title }} - {{ item.event }} - {{ item.location }}, {{ item.year }}
        {% comment %}
        {% if item.description %} <br> {{ item.description }}
        {% endif %}
        {% endcomment %}
    </li>
{% endif %}
{% endfor %}
</ul>

