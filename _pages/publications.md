---
layout: page
permalink: /publications/
title: Publications
years: [2022,2021, 2020]
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
