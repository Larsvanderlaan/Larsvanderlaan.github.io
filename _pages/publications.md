---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 1
no_tracking: true
---

Below are selected methodological and theoretical contributions, organized by research area. For the complete publication record, including applied collaborations, see my [Google Scholar](https://scholar.google.com/citations?user=0bwP0i4AAAAJ) profile or [CV](/cv/).

<nav class="publication-topics" aria-label="Publication topics">
  <a href="#dml">Debiased inference</a>
  <a href="#ope">Offline RL &amp; OPE</a>
  <a href="#sequential">Sequential inference</a>
  <a href="#hte">Heterogeneous effects</a>
  <a href="#calibration">Calibration</a>
  <a href="#software">Software</a>
  <a href="#notes">Notes &amp; references</a>
</nav>

<div class="publications">

  <h2 id="dml">Debiased machine learning and semiparametric inference</h2>
  <div class="pub-section">
    <div class="pub-list">
      {% bibliography -f {{site.scholar.bibliography}} --query @*[keywords~=web_dml] --group_by none %}
    </div>
  </div>
  
  <h2 id="ope">Offline reinforcement learning and off-policy evaluation</h2>
  <div class="pub-section">
    <div class="pub-list">
      {% bibliography -f {{site.scholar.bibliography}} --query @*[keywords~=web_ope] --group_by none %}
    </div>
  </div>

  <h2 id="sequential">Inverse reinforcement learning and sequential causal inference</h2>
  <div class="pub-section">
    <div class="pub-list">
      {% bibliography -f {{site.scholar.bibliography}} --query @*[keywords~=web_sequential] --group_by none %}
    </div>
  </div>


  <h2 id="hte">Heterogeneous treatment effects</h2>
  <div class="pub-section">
    <div class="pub-list">
      {% bibliography -f {{site.scholar.bibliography}} --query @*[keywords~=web_hte] --group_by none %}
    </div>
  </div>

  <h2 id="calibration">Calibration and predictive inference</h2>
  <div class="pub-section">
    <div class="pub-list">
      {% bibliography -f {{site.scholar.bibliography}} --query @*[keywords~=web_calibration] --group_by none %}
    </div>
  </div>
  
  <h2 id="software">Software and research materials</h2>
  <div class="pub-section">
    <div class="pub-list">
      {% bibliography -f {{site.scholar.bibliography}} --query @*[keywords~=web_software] --group_by none %}
    </div>
  </div>

  <h2 id="notes">Notes and reference works</h2>
  <div class="pub-section">
    <div class="pub-list">
      {% bibliography -f {{site.scholar.bibliography}} --query @*[keywords~=web_notes] --group_by none %}
    </div>
  </div>

</div>
