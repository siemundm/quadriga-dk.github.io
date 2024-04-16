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
      {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
      {%- for post in posts -%}
      <li>
        <span class="post-meta">{{ post.date | date: date_format }}</span>
        <h3>
          <a class="post-link" href="{{ post.url | relative_url }}">
            {{ post.title | escape }}
          </a>
        </h3>
        {%- if site.show_excerpts -%}
          {{ post.excerpt }}
        {%- endif -%}
      </li>
      {%- endfor -%}
    </ul>

