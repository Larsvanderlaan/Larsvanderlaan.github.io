---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 1
---

Below are selected methodological and theoretical contributions. For a complete list of publications, including applied work, see my [Google Scholar](https://scholar.google.com/citations?user=0bwP0i4AAAAJ&hl=en&authuser=1) profile.

<div class="publications">

<h3>Calibration for causal inference</h3>
<div class="pub-section">
  <div class="pub-list collapsed">
    {% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=causalcal] %}
  </div>
  <button class="toggle-btn" onclick="toggleSection(this)">Show more</button>
</div>

<h3>Debiased and efficient estimation</h3>
<div class="pub-section">
  <div class="pub-list collapsed">
    {% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=effest] %}
  </div>
  <button class="toggle-btn" onclick="toggleSection(this)">Show more</button>
</div>

<h3>Causal inference methodology</h3>
<div class="pub-section">
  <div class="pub-list collapsed">
    {% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=methods] %}
  </div>
  <button class="toggle-btn" onclick="toggleSection(this)">Show more</button>
</div>

<h3>Conformal prediction and predictive uncertainty</h3>
<div class="pub-section">
  <div class="pub-list collapsed">
    {% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=calibration] %}
  </div>
  <button class="toggle-btn" onclick="toggleSection(this)">Show more</button>
</div>

<h3>Software and computational tools</h3>
<div class="pub-section">
  <div class="pub-list collapsed">
    {% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=software] %}
  </div>
  <button class="toggle-btn" onclick="toggleSection(this)">Show more</button>
</div>

</div>

<script>
function toggleSection(button) {
  const list = button.previousElementSibling;
  list.classList.toggle("collapsed");
  button.textContent = list.classList.contains("collapsed") ? "Show more" : "Show less";
}
</script>
