---
layout: page
title: Proyectos
permalink: /proyectos/
order: 2
---

# Mis Proyectos

Aquí puedes ver mis trabajos recientes:

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