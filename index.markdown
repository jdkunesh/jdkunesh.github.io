---

layout: home

---

<ul>
  {% for item in site.data.navigation.primary %}
    <a href="{{ site.baseurl }}{{ item.url }}">
      <li>{{ item.text}}</li>
    </a>
  {% endfor %}
</ul>


* Chicago, IL
* [Github](https://github.com/jdkunesh)
* [Twitter](http://www.twitter.com/jdkunesh/)
* [LinkedIn](http://www.linkedin.com/in/jdkunesh/)
