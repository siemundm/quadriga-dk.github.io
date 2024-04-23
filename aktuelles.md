---
layout: page
title: Aktuelles
icon: ![aktuelles](https://github.com/quadriga-dk/quadriga-dk.github.io/assets/166709081/b40d0226-96cb-4fe1-9703-50257d093545)
permalink: /aktuelles/
---

<ul>
{% for post in site.posts %}
<p>
{{ post.date | date: "%b %-d, %Y"}}<br>
<a href="{{ post.url }}">{{ post.title }}</a><br>
</p>
{% endfor %}
</ul>

