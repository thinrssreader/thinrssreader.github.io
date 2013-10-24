---
layout: page
title: crimefighter.github.io
tagline:
---
{% include JB/setup %}

<ul class="posts unstyled">
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>
      <small>{{ post.date | date_to_string }}</small>
    </li>
  {% endfor %}
</ul>
