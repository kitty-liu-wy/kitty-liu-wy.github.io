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


<h3 id="articles" style="margin-top: 3.3rem; margin-bottom: 0.3rem;">
  peer-reviewed articles
</h3>
{% bibliography -f articles %}

<h3 id="proceedings"><h3 style="margin-top: 3.3rem; margin-bottom: 0.3rem;">
    conference proceedings
</h3>
{% bibliography -f proceedings %}

<h3 id="reviewed_presentations"><h3 style="margin-top: 3rem; margin-bottom: 0.3rem;">
    peer-reviewed presentations
</h3>
  {% bibliography -f reviewed_presentations %}

<h3 id="theses"><h3 style="margin-top: 3.3rem; margin-bottom: 0.3rem;">
    theses
</h3>
{% bibliography -f theses %}


</div>
