---
layout: default
title: Welcome
description: Discover mossy paths, drying herbs, and timeless crafts.
---

<section class="hero">
  <h2>Under the Brambles</h2>
  <p>A place for mossy paths, drying herbs, well-worn recipes, and timeless crafts.</p>
</section>

<section>
  <h3>Latest Posts</h3>
  <ul>
    {% for post in site.posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a> <small>{{ post.date | date: "%B %-d, %Y" }}</small></li>
    {% endfor %}
  </ul>
</section>
