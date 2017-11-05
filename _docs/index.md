---
title: Docs
author: CanalDBA
layout: page
---

Aqui encontraras los recursos necesarios para adentrarte en las tecnologias
que esta comunidad maneja (WIP).


{% for item in site.docs %}
{% if item.title != "Docs" %}
  <h2>{{ item.title }}</h2>
  <p>{{ item.description }}</p>
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
{% endif %}
{% endfor %}