---
layout: page
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}

<ul class="posts unstyled">
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h3>
      <small>{{ post.date | date_to_string }}</small>
    </li>
  {% endfor %}
</ul>
