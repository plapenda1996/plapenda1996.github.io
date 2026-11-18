---
layout: page
permalink: /publications/
title: publications
description: Journal articles and conference proceedings in reverse chronological order. * denotes equal contribution.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>journal articles</h2>

{% bibliography --query @article %}

<h2>conference proceedings</h2>

{% bibliography --query @inproceedings %}

</div>

## patent

L. Gao, Z. Zang, **D. Y. Kim**, "High-speed volumetric imaging of deep-tissue dynamics in vivo with NIR-II squeezed light-field microscopy," provisional patent application, 2026.
