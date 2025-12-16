---
layout: page
title: Bookmarks
permalink: /bookmarks/
---

<ul class="post-list">
  {% for bookmark in site.bookmarks %}
    <li>
      <h4>
        <a class="post-link" href="{{ bookmark.url | relative_url }}">
          {{ bookmark.title | escape }}
        </a>
      </h4>
      <div class="post-content">
        {{ bookmark.excerpt }}
      </div>
    </li>
  {% endfor %}
</ul>
