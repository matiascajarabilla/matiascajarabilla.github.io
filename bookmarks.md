---
layout: page
title: Bookmarks
permalink: /bookmarks/
---

### Bookmarks

<ul>
  {% for bookmark in site.bookmarks %}
    <li>
      <a href="{{ bookmark.url | relative_url }}">{{ bookmark.title }}</a>
      <p>{{ bookmark.excerpt | strip_html | truncate: 100 }}</p>
    </li>
  {% endfor %}
</ul>
