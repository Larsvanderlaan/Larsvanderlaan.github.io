---
layout: page
permalink: /publications/
title: publications
description: Below are selected methodological and theoretical contributions.  

nav: true
nav_order: 1
---

For a complete list of publications, including applied work, see my [Google Scholar](https://scholar.google.com) profile.

<div class="publications">


<h3>Calibration for causal inference</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=causalcal] %}

<h3>Debiased and efficient estimation</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=effest] %}

<h3>Causal inference methodology</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=methods] %}

<h3>Conformal prediction and predictive uncertainty</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=calibration] %}

<h3>Software and computational tools</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=software] %}


</div>
