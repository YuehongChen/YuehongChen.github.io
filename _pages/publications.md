---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<h2 class="pub-section">first-author publications</h2>

<div class="publications">

{% bibliography %}

</div>

<h2 class="pub-section">co-authored publications</h2>

<div class="publications">

{% bibliography --file coauthored %}

</div>
