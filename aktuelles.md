---
layout: page
title: Aktuelles
permalink: /aktuelles/
---

<ul>
  {% for post in site.posts %}
    <p>
      <a href="{{ post.url }}">{{ post.title }}</a><br> 
      {{ post.date | date: date_format}}<br>
        </p>
  {% endfor %}
</ul>

xxxxxxx

