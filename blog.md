---
layout: page
title: Blog
permalink: /Blog/
---

<ul class="post-list">
    {% for page in site.categories.blog %}
      <li>
      <h1><a href="{{ page.url }}">{{ page.title }}</a></h1>
      <p>publikováno {{ page.date }}</p>
      </li>
    {% endfor %}
</ul>
