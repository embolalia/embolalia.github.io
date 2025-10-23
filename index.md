My name starts with an E. There are other letters but they're very blurry. Most people call me Else, as in `if` <sup><small>(dot com)</small></sup>. You can email me at
`else@(this domain)`. On the fediverse I'm <a rel="me" href="https://furry.engineer/@else">@else@furry.engineer</a>.

This website is everything I know. A lot of it is [Unspeakable](/unspeakable). Some of it is [Giraffes](/giraffes). Just [start from the beginning](/story), and eventually my [Tribute](/tribute) will make sense.

---

<h3>Most recent posts</h3>
<ul>
  {% for post in site.posts limit:3%}
    <li>
      <small><i>{{ post.date | date: "%Y-%m-%d" }}</i></small> - <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<h3>Posts by tag</h3>

{% for tag in site.tags %}
  <h4>{{ tag[0] }}</h4>
  <ul>
    {% for post in tag[1] %}
      <li><small><i>{{ post.date | date: "%Y-%m-%d" }}</i></small> - <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

<h3>Posts by date</h3>

<ul>
  {% for post in site.posts %}
    <li>
      <small><i>{{ post.date | date: "%Y-%m-%d" }}</i></small> - <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>