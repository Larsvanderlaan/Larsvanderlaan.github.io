---
layout: page
permalink: /publications/
title: publications
description: Below are selected methodological and theoretical contributions. For a complete list of publications, including applied work, see my [Google Scholar](https://scholar.google.com) profile.

nav: true
nav_order: 1
---

[Google Scholar](https://scholar.google.com/citations?user=0bwP0i4AAAAJ&hl=en)

<div class="publications">


<h3>Causal inference: calibration and learning theory</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=causalcal] %}

<h3>Debiased and efficient estimation</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=effest] %}

<h3>Causal inference: methodological contributions</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=methods] %}

<h3>Calibration and distribution-free uncertainty quantification</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=calibration] %}

<h3>Software</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=software] %}


</div>
