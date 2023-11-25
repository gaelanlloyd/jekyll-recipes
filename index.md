---
layout: default
title: Recipes
permalink: /
---

<ul class="pl1">
{% for recipe in site.recipes %}
  <li><a href="{{ recipe.url }}">{{ recipe.title }}</a>{% if recipe.description %} &middot; {{ recipe.description }}{% endif %}{% if recipe.yield %} &middot; {{ recipe.yield }}{% endif %}</li>
{% endfor %}
</ul>

<hr />

<p><a href="{{ site.urlRepo }}" target="_blank">GitHub</a></p>
