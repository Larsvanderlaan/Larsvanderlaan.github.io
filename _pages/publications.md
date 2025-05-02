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


<h3>Calibration for Causal Inference</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=causalcal] %}

<h3>Debiased and Efficient Estimation</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=effest] %}

<h3>Causal Inference Methodology</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=methods] %}

<h3>Conformal Prediction and Predictive Uncertainty</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=calibration] %}

<h3>Software and Computational Tools</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=software] %}


</div>
