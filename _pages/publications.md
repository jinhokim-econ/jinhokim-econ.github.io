---
layout: page
permalink: /publications/
title: research
description: 
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<!-- {% include bib_search.liquid %} -->

<div class="publications">
  <h2 style="margin-bottom: 20px;">Working Papers</h2>
  {% bibliography --query @*[category=Working Papers] %}

  <div style="margin-top: 40px;"></div>

  <h2 style="margin-bottom: 20px;">Work in Progress</h2>
  {% bibliography --query @*[category=Work in Progress] %}
</div>
