---
layout: page
permalink: /publications/
title: publications
description: Selected Publications. co-first authors; co-corresponding authors. 
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<!-- {% include bib_search.liquid %} -->

<br />
<h2> Main publications </h2>

<div class="publications">

{% bibliography --group_by year --query @*[category=Main] %}

<br />
<h2> Contributed publications </h2>

{% bibliography --group_by year --query @*[category=Contributed] %}

<br />
<h2> Template publications </h2>

{% bibliography --group_by none --query @*[category=Template] %}

</div>
