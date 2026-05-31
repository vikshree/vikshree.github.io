---
layout: page
permalink: /publications/
title: Publications
# description: Publications and patents in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<!-- {% include bib_search.liquid %} -->

<div class="publications">

<h2>Peer-reviewed Journal and Conference Articles</h2>

{% bibliography --query @article,@inproceedings,@incollection,@book,@phdthesis,@mastersthesis,@techreport %}

<h2>Approved Patents</h2>

{% bibliography --query @patent, @misc %}

</div>
