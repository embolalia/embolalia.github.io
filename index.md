My name starts with an E. There are other letters but they're very blurry. Most people call me Else, as in `if` <sup><small>(dot com)</small></sup>. You can email me at
`else@(this domain)`. On the fediverse I'm <a rel="me" href="https://furry.engineer/@else">@else@furry.engineer</a>.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>