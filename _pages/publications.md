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

<h3>Causal Inference</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=causal] %}

<h3>Calibration Methods</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=causalcalibration] %}

<h3>Conference Papers</h3>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=calibration] %}

</div>
