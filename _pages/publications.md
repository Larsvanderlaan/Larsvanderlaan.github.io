---
layout: page
permalink: /publications/
title: publications
description: For a complete list of my research publications, check out my Google Scholar profile.
nav: true
nav_order: 1
---

[Google Scholar](https://scholar.google.com/citations?user=0bwP0i4AAAAJ&hl=en)

<div class="publications">


<h3>Calibration for Causal Inference</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=causalcal] %}

<h3>Semiparametric Efficiency and Debiased Estimation</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=effest] %}

<h3>Causal Inference: Methods and Theory</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=causal] %}

<h3>Calibration and Distribution-Free Uncertainty Quantification</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=calibration] %}

<h3>Computing software</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=software] %}


</div>
