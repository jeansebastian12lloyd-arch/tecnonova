---
layout: home
title: TecnoNova
---

# Bienvenido a **TecnoNova**

TecnoNova es un blog dedicado a la innovación y las últimas tendencias en tecnología.  
Aquí encontrarás artículos sobre inteligencia artificial, gadgets, programación y recursos para aprender.

## Entradas recientes

<ul>
  {% for post in site.posts limit:3 %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

Visita las entradas para leer más.
