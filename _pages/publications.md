---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 1
---

Below are selected methodological and theoretical contributions. For a complete list of publications, including applied work, see my [Google Scholar](https://scholar.google.com/citations?user=0bwP0i4AAAAJ&hl=en&authuser=1) profile.

<div class="publications">

  <h3>Debiased machine learning and efficiency theory</h3>
  <div class="pub-section">
    <div class="pub-list">
      {% bibliography -f {{site.scholar.bibliography}} --query @*[keywords~=effest] %}
    </div>
  </div>
  
    <h3>Dynamic decision-making and heterogeneous treatment effects</h3>
  <div class="pub-section">
    <div class="pub-list">
      {% bibliography -f {{site.scholar.bibliography}} --query @*[keywords~=dynamic] %}
    </div>
  </div>

  <h3>Causal inference methodology</h3>
  <div class="pub-section">
    <div class="pub-list">
      {% bibliography -f {{site.scholar.bibliography}} --query @*[keywords~=methods] %}
    </div>
  </div>


  <h3>Conformal prediction and predictive uncertainty</h3>
  <div class="pub-section">
    <div class="pub-list">
      {% bibliography -f {{site.scholar.bibliography}} --query @*[keywords~=calibration] %}
    </div>
  </div>

  <h3>Software and computational tools</h3>
  <div class="pub-section">
    <div class="pub-list">
      {% bibliography -f {{site.scholar.bibliography}} --query @*[keywords~=software] %}
    </div>
  </div>

</div>
