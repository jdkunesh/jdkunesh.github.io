---

layout: home

---

<h2>Howdy!</h2>

<p>inspirational statement like a book cover</p>
<p>lover's quarrel with tech: design, biz, code intersection.</p>
<ul>
  {% for item in site.data.navigation.primary %}
    <a href="{{ site.baseurl }}{{ item.url }}">
      <li>{{ item.text}}</li>
    </a>
  {% endfor %}
</ul>

