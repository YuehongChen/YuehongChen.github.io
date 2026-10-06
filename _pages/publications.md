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

<style>
.pub-section{font-size:1.3rem;font-weight:500;margin:2.2rem 0 .3rem;padding-bottom:.4rem;border-bottom:1px solid var(--global-divider-color)}
.publications ol.bibliography li{padding:.9rem 0;border-bottom:1px solid var(--global-divider-color)}
.publications ol.bibliography li:last-child{border-bottom:0}
.bibsearch-form-input{background:var(--global-bg-color);color:var(--global-text-color);border:1px solid var(--global-divider-color)}
</style>

<h2 class="pub-section">First-author</h2>

<div class="publications">

{% bibliography --group_by none %}

</div>

<h2 class="pub-section">Co-authored</h2>

<div class="publications">

{% bibliography --file coauthored --group_by none %}

</div>
