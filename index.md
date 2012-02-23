---
layout: page
title: Crowdsourcing
---

Bienvenido a la web sobre Crowdsourcing para Recuperación y Acceso a la Información.

## Temas disponibles

<ul class="posts">
  {% for page in site.pages %}
    {% if page.group == 'navigation' %}
    <li><a href="{{ BASE_PATH }}{{ page.url }}">{{ page.title }}</a> &laquo; <span>{{ site.authors[page.author].name }}</span></li>
    {% endif %}
  {% endfor %}
</ul>
