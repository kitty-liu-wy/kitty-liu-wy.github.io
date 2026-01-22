---
layout: page
permalink: /publications_presentations/
title: publications & presentations
description: 
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<p> 
This page lists my research output. Please email me if you would like a copy of anything that isn't already linked!
</p>

<ul>
    <li><a href="#articles"><b>peer-reviewed journal articles</b></a></li>
    <li><a href="#proceedings"><b>conference proceedings</b></a></li>
    <li><a href="#reviewed_presentations"><b>peer-reviewed presentations</b></a></li>
    <li><a href="#theses"><b>theses</b></a></li>

</ul>


<div class="publications">


<h3 id="articles" style="margin-top: 4.5rem; margin-bottom: -1rem;">
  peer-reviewed articles
</h3>
<!-- adding in the following manually codes in a divider under the heading
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;"> 
-->
{% bibliography -f articles %}

<h3 id="proceedings"><h3 style="margin-top: 4.5rem; margin-bottom: -1rem;">
    conference proceedings
</h3>
{% bibliography -f proceedings %}

<h3 id="reviewed_presentations"><h3 style="margin-top: 4.5rem; margin-bottom: -1rem;">
    peer-reviewed presentations
</h3>
  {% bibliography -f reviewed_presentations %}

<h3 id="theses"><h3 style="margin-top: 4.5rem; margin-bottom: -1rem;">
    theses
</h3>
{% bibliography -f theses %}


</div>
