---
layout: page
title: open theses
permalink: /theses/
description: Thesis projects currently available. Each thesis is a specific 6 to 12 month block within one of the larger research projects.
nav: true
nav_order: 5
horizontal: false
---

<!-- pages/theses.md: same card layout as projects, reading the "theses" collection -->
<div class="projects">
{% assign sorted_projects = site.theses | sort: "importance" %}
{% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
{% else %}
  <div class="row row-cols-1 row-cols-md-3">
  {% for project in sorted_projects %}
    {% include projects.liquid %}
  {% endfor %}
  </div>
{% endif %}
</div>
