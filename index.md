---
layout: default
title: Eagles Analytics Blog
---

# Eagles Analytics Blog
A data-driven look at the Philadelphia Eagles using NFL stats, analytics, and AI.

## Weekly Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>({{ post.date | date: "%B %d, %Y" }})</span>
    </li>
  {% endfor %}
</ul>
