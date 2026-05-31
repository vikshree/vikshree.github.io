---
layout: page
title: Research
permalink: /research/
description: My research projects and ongoing work.
nav: true
nav_order: 3
---

<!-- pages/research.md -->
<div class="projects">
{% assign sorted_research = site.research | sort: "importance" %}

<!-- Generate stacked research items (full-width) -->
<div class="research-list">
  {% for project in sorted_research %}
    {% include research.liquid %}
  {% endfor %}
</div>

</div>