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


Mal schauen ob das klappt:


<ul>
<li>
        <span class="post-meta">{{ post.date | date: date_format }}</span>
        <h3>
          <a class="post-link" href="{{ post.url | relative_url }}">
            {{ post.title | escape }}
          </a>
        </h3>
      </li>
</ul>
