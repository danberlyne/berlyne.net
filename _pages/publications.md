---
layout: page
permalink: /research/
title: research
description:
years: [2023, 2022, 2021, 2015, 2014]
nav: true
nav_order: 1
---

My research is in geometric group theory, an area of mathematics devoted to studying groups as geometric objects in order to solve algebraic and algorithmic problems, as well as problems in other fields. For example, geometric group theory was used by Agol and Wise to solve Thurston’s virtual Haken conjecture, a major open problem in low-dimensional topology, and by Sela to solve the famed Tarski conjecture in first-order logic. 

The methods of geometric group theory have also had extraordinary success outside of mathematics, with Carlsson’s development of persistent homology in topological data analysis, Ghrist’s applications of braid groups in robotics, and recent exciting applications of graph braid groups in topological quantum computing by Maciazek et al.

<!-- My research focuses on non-positive curvature in groups. I am especially interested in groups acting on cube complexes, as well as hierarchical hyperbolicity, which is a tool to study groups from a geometric point of view by exploiting patterns of hyperbolic behaviour occurring within them. This tool applies to a wide range of groups, including: -->

<!-- right-angled Artin groups, right-angled Coxeter groups, and fundamental groups of special cube complexes;
- mapping class groups and Teichmüller space;
- 3-manifold groups containing no Nil or Sol components;
- graph products of hyperbolic groups;
- braid groups. -->

My research focuses on non-positive curvature in groups. I am especially interested in graph braid groups, as well as hierarchical hyperbolicity, which is a tool to study groups from a geometric point of view by exploiting patterns of hyperbolic behaviour occurring within them. Recently, I have been studying random quotients of hierarchically hyperbolic groups and using cube complexes to study non-positive curvature in graph braid groups. I have also written code to implement algorithms detailed in [my paper on graph braid groups](https://www.worldscientific.com/doi/epdf/10.1142/S0218196723500583). For example, I have written a [program that computes free splittings of graph braid groups](https://github.com/danberlyne/graph-braid-splitter) and, joint with [Tomasz Maciazek](https://research-information.bris.ac.uk/en/persons/tomasz-maciazek), a [program that computes presentations of graph braid groups](https://github.com/danberlyne/graph-braid-presenter).

A copy of my research statement is available [here](/assets/pdf/Research_statement.pdf).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
