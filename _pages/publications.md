---
layout: page
permalink: /publications/
title: publications
description:  X for exploring the unknown.
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<!-- {% include bib_search.liquid %} -->

<h2> main publications </h2>
#: first authors; *: corresponding authors.

<div class="publications">

{% bibliography --group_by year --query @*[category=Main] %}

<h2> contributed publications </h2>

{% bibliography --group_by year --query @*[category=Contributed] %}


</div>
