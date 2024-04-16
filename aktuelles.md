---
layout: page
title: Aktuelles
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

