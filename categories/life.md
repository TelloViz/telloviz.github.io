---
layout: page
title: life
permalink: /blog/categories/life/
---

<h5> Posts by Category : {{ page.title }} </h5>

<div class="card">
{% for post in site.categories.life %}
 <ul class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></ul>
{% endfor %}
</div>