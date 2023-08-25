---
layout: page
permalink: /research/
title: research
description:
years: [2023, 2022, 2021, 2015, 2014]
nav: true
nav_order: 1
---

My research focuses on non-positive curvature in groups. I am especially interested in groups acting on cube complexes, as well as hierarchical hyperbolicity, which is a tool to study groups from a geometric point of view by exploiting patterns of hyperbolic behaviour occurring within them. This tool applies to a wide range of groups, including:

- right-angled Artin groups, right-angled Coxeter groups, and fundamental groups of special cube complexes;
- mapping class groups and Teichmüller space;
- 3-manifold groups containing no Nil or Sol components;
- graph products of hyperbolic groups;
- braid groups.

Recently, I have been studying random quotients of hierarchically hyperbolic groups and using cube complexes to study non-positive curvature in graph braid groups. I am also working on writing code to implement algorithms detailed in my paper on [graph braid groups](https://arxiv.org/pdf/2209.03860.pdf). For example, I have written a [programme that computes free splittings of graph braid groups](https://github.com/danberlyne/graph-braid-splitter) and, joint with [Tomasz Maciazek](https://research-information.bris.ac.uk/en/persons/tomasz-maciazek), a [programme that computes presentations of graph braid groups](https://github.com/danberlyne/graph-braid-presenter).

A copy of my research statement is available [here](/assets/pdf/Research_statement.pdf).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
