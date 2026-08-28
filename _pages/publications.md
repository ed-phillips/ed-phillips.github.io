---
layout: page
permalink: /publications/
title: publications
description: Peer-reviewed work and preprints, most recent first.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography">peer-reviewed</h2>

{% bibliography -f publications --group_by none %}

<h2 class="bibliography">preprints & under review</h2>

{% bibliography -f preprints --group_by none %}

</div>
