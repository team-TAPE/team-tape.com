---
layout: default
---

# Announcement

<div id="posts">
  {% for post in site.categories.resources %}
    <a href="{{ site.url }}{{ post.url }}"><h2>{{ post.title }}</h2></a>
    <p class="post-meta">
    <p> {{ post.excerpt }} </p>
    <br>
  {% endfor %}

</div> <!-- End Posts -->
