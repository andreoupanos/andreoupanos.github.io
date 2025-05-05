---
layout: archive
title: "Teaching"
permalink: /teaching/
collection: teaching
author_profile: true
---

This page lists selected courses and notes I've created or contributed to.

{% for post in site.teaching %}
  {% include archive-single.html type="grid" %}
{% endfor %}