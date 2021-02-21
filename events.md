---
title: Events
published: true
layout: default

---

<h1>Events</h1>

<h2>Speaking</h2>
<ul>
{% for event in site.data.events %}
{% if event.live %} 
 <li>
    <a href="{{event.url}}">{{ event.title }}</a> - {{event.event}} ({{ event.year }})
    <p>{{ event.location }}</p>
    {% if event.description %}<p>{{ event.description }}</p>{% endif %}
 </li>
{% endif %}
{% endfor %}
</ul>

<h2>Press</h2>
<ul>
{% for article in site.data.press %}
     <li>
    {% if article.feature %}<p>{{article.feature}}</p>{% endif %}
    {% if article.publisher %}{{article.publisher}}{% endif %} <a href="{{article.url}}">{{ article.title }}</a> ({{article.year}}) 
    {% if article.quote %}<p><em>{{article.quote}}</em></p>{% endif %}
    {% if article.description %}<p>{{article.description}}</p>{% endif %}
    {% if article.media %}<p>{{article.media}}</p>{% endif %}
    </li>
{% endfor %}
</ul>

