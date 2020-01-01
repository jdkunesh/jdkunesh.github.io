---

layout: home

---

<div class="card-deck">
      {% for item in site.data.eras %}
        <a href="{{ site.baseurl }}{{ item.url }}">
          <div class="card card-home">
            <img src="{{ item.image }}" alt="{{ item.alt_text }}"/>
            <div class="card-body">
                <h2>{{ item.title }}</h2>
            </div>
          </div>
        </a>
      {% endfor %}
</div>

* Chicago, IL
* [Github](https://github.com/jdkunesh)
* [Twitter](http://www.twitter.com/jdkunesh/)
* [LinkedIn](http://www.linkedin.com/in/jdkunesh/)
