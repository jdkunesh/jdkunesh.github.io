---
title: Press
published: false

---


Contact jdkunesh@gmail.com for press inquiries.

A common press kit

I've spoken at companies including Google, Intuit, and Microsoft and at conferences like SXSW, UX Week, BAYCHI, Web Visions and more. His work has been featured in the New York Times, the Atlantic Monthly, BusinessWeek, TIME, Forbes, Crain's, the Chicago Tribune and others.

Photos



<ul>

{% for item in site.data.press %}

<li><a href="{{ item.url }}">{{ item.title }} - {{ item.organization }}</a>, {{ item.year }}</li>


{% endfor %}
</ul>

