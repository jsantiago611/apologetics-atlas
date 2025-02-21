---
title: Index
permalink: /noteindex/index.html
description: 'You can use this starter as a template for your blog and you are ready to go! But there are some adjustments you have to make.'
layout: page
---

This page is modeled after the "Index" page of a Zettelkasten. It's ordered by alphabetical order. The idea is that every main section is listed here, and will lead to main sections that you can further explore. 

### Explore the Index

<!-- loop docs -->
{% set itemList = collections.docs %}
{% include 'partials/details.njk' %}

{% css "local" %}
  {% include "css/custom-card.css" %}
{% endcss %}
 