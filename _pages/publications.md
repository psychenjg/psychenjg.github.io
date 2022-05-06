---
layout: page
permalink: /publications/
title: publications
description: Electronic versions are provided as a professional courtesy to ensure timely dissemination of academic work for individual, noncommercial purposes. Copyright and all rights therein reside with the respective copyright holders, as stated in each paper. These files may not be reposted without permission.
years: [2022,2021,2019,2015]
nav: true
---
<!-- _pages/publications.md -->

<div class="publications">

{%- for y in page.years %}

<h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
