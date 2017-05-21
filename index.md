---
layout: page
title: Home
---

# Vítejte na stránkách věnovaných festivalu Jeden svět Tišnov

See the posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
