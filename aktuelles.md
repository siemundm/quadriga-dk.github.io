---
layout: page
title: Aktuelles
permalink: /aktuelles/
---

<ul>
  {% for post in site.posts %}
    <p>
      <a href="{{ post.url }}">{{ post.title }}</a><br>
        </p>
  {% endfor %}
</ul>

xxx

