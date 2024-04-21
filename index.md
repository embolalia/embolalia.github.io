My name is Else. As in `if` <sup><small>(dot com)</small></sup>. (Elsie 
Powell, legally.) I use they/them pronouns. You can email me at
`else@(this domain)`, or at `me@(my legal name).com`. On the fediverse I'm
<a rel="me" href="https://bluelupine.social/@else">@else@bluelupine.social</a>
and <a rel="me" href="https://furry.engineer/@else">@else@furry.engineer</a>.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>