---
layout: page
title: tareas
permalink: /tareas/
---
{%- for practica in site.tareas %}
  {%- if practica.visible %}
{{ practica.name | slice: 0, 2  }}.  <a href="/
p04-t0-aprender-jekyll-alu0100318166{{ practica.url }}">Práctica {{ practica.name }}</a>
  {%- endif %}
{%- endfor %}

