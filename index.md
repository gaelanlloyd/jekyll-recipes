---
layout: default
title: Recipes
permalink: /
---

{% for recipe in site.recipes %}
  <p><a href="{{ recipe.url }}">{{ recipe.title }}</a></p>
{% endfor %}
