---
layout: page
title: Proyectos
permalink: /proyectos/
---

<ul class="post-list">
  {% for proyecto in site.proyectos %}
    <li>
      <h4>
        <a class="post-link" href="{{ proyecto.url | relative_url }}">
          {{ proyecto.title | escape }}
        </a>
      </h4>
      <div class="post-content">
        {{ proyecto.excerpt }}
      </div>
    </li>
  {% endfor %}
</ul>
