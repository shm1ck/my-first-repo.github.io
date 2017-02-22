---
layout: post
title: Knihy

---

<ul class="post-list">
    {% for post in site.tags.kniha %}
      <li>
        {% if post.images %}
            <a href="{{ post.url }}">
                <img src="{{ site.config.img.orig_url }}{{ post.images|first.image }}" />
            </a>
        {% endif %}
      </li>
    {% endfor %}
  </ul>
