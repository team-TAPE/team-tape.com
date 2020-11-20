---
layout: default
---

<div id="posts">
  <h1>Games</h1>

  {% for post in site.categories.games %}
    <a href="{{ site.url }}{{ post.url }}"><h2>{{ post.title }}</h2></a>
    <p> {{ post.excerpt }} </p>
  {% endfor %}

</div> <!-- End Posts -->
