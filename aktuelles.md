---
layout: page
title: Aktuelles
permalink: /aktuelles/
---

<ul>
  {% for post in site.posts %}
    <p>
      <a href="{{ post.url }}">{{ post.title }}</a><br>
      <p><small><strong>{{ post.date | date: date_format }}</strong><br>
        </p>
  {% endfor %}
</ul>

xxx

