---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home

---


<div class="card-deck">
      {% for item in site.data.eras %}
        <a href="{{ site.baseurl }}{{ item.url }}">
          <div class="card card-home">
            <div class="card-body">
                <h3>{{ item.title }}</h3>
              <p class="card-text"><img src="{{ item.image }}" alt="{{ item.alt_text }}"/></p>
            </div>
          </div>
        </a>
      {% endfor %}
</div>

* Chicago, IL
* [Github](https://github.com/jdkunesh)
* [Twitter](http://www.twitter.com/jdkunesh/)
* [LinkedIn](http://www.linkedin.com/in/jdkunesh/)


