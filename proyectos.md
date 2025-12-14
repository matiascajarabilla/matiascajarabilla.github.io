---
layout: page
title: Proyectos
permalink: /proyectos/
---

<ul>
  {% for proyecto in site.proyectos %}
    <li>
      <a href="{{ proyecto.url }}">
        <h3>{{ proyecto.title }}</h3>
      </a>
      <p>{{ proyecto.description }}</p>
    </li>
  {% endfor %}
</ul>