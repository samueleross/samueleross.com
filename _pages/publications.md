---
layout: research
permalink: /research/
title: Research
description: 
years: [2024]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">
<h1>Working Papers</h1>
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
