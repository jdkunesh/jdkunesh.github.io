---

layout: home
title: Jason Kunesh's CyberPalace

---
<h2>Howdy!</h2>
<p>inspirational statement like a book cover</p>
<p>lover's quarrel with tech: design, biz, code intersection.</p>

{% for item in site.data.work %}
<a href="{{ site.baseurl }}{{ item.url }}">
<img src="{{ item.image }}" alt="{{ item.alt_text }}" />
<h2>{{ item.title }}</h2>
</a>
{% endfor %}
