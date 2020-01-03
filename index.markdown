---

layout: home
title: Jason Kunesh's CyberPalace 
---

<div class="pure-g">
    <div class="pure-u-1 pure-u-md-1-2 p1rem">
    <h2>Howdy!</h2>
    <p>inspirational statement like a book cover</p>
    <p>lover's quarrel with tech: design, biz, code intersection.</p>
    </div>
</div>
<div class="pure-g">
 {% for item in site.data.work %}
   <div class="pure-u-1 pure-u-md-1-3 card">
        <a href="{{ site.baseurl }}{{ item.url }}">
        <img src="{{ item.image }}" alt="{{ item.alt_text }}" class="pure-img" />
        <h2>{{ item.title }}</h2>
        </a>
    </div>
{% endfor %}
</div>
