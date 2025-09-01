---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 1
---

Below are selected methodological and theoretical contributions. For a complete list of publications, including applied work, see my [Google Scholar](https://scholar.google.com/citations?user=0bwP0i4AAAAJ&hl=en&authuser=1) profile.

<div class="publications">

<h3>Automatic debiasing and efficient estimation theory</h3>
<div class="pub-section">
  <div class="pub-list collapsed">
    {% bibliography -f {{site.scholar.bibliography}} --query @*[keywords~=effest] %}
  </div>
  <button class="toggle-btn" onclick="toggleSection(this)" aria-expanded="false">Show more</button>
</div>

<h3>Causal inference methodology</h3>
<div class="pub-section">
  <div class="pub-list collapsed">
    {% bibliography -f {{site.scholar.bibliography}} --query @*[keywords~=methods] %}
  </div>
  <button class="toggle-btn" onclick="toggleSection(this)" aria-expanded="false">Show more</button>
</div>

<h3>Dynamic decision-making and heterogeneous treatment effects</h3>
<div class="pub-section">
  <div class="pub-list collapsed">
    {% bibliography -f {{site.scholar.bibliography}} --query @*[keywords~=dynamic] %}
  </div>
  <button class="toggle-btn" onclick="toggleSection(this)" aria-expanded="false">Show more</button>
</div>

<h3>Conformal prediction and predictive uncertainty</h3>
<div class="pub-section">
  <div class="pub-list collapsed">
    {% bibliography -f {{site.scholar.bibliography}} --query @*[keywords~=calibration] %}
  </div>
  <button class="toggle-btn" onclick="toggleSection(this)" aria-expanded="false">Show more</button>
</div>

<h3>Software and computational tools</h3>
<div class="pub-section">
  <div class="pub-list collapsed">
    {% bibliography -f {{site.scholar.bibliography}} --query @*[keywords~=software] %}
  </div>
  <button class="toggle-btn" onclick="toggleSection(this)" aria-expanded="false">Show more</button>
</div>

</div>

<script>
(function () {
  function pubItems(listEl) {
    if (!listEl) return [];
    // Handle common Jekyll Scholar outputs:
    //  - <ol class="bibliography"><li>…</li></ol>
    //  - CSL-based <div class="csl-entry">…</div>
    //  - legacy <div class="entry">…</div>
    return listEl.querySelectorAll(
      '.bibliography > li, .bibliography > *, :scope > .csl-entry, :scope > .entry'
    );
  }

  function setBtnState(btn, collapsed) {
    if (!btn) return;
    btn.textContent = collapsed ? 'Show more' : 'Show less';
    btn.setAttribute('aria-expanded', String(!collapsed));
  }

  document.addEventListener('DOMContentLoaded', function () {
    document.querySelectorAll('.pub-section').forEach(function (sec) {
      var list = sec.querySelector('.pub-list');
      var btn  = sec.querySelector('.toggle-btn');
      if (!list || !btn) return;

      var items = pubItems(list);
      // Hide the toggle if there are 2 or fewer publications
      if (items.length <= 2) {
        btn.style.display = 'none';
      } else {
        // Ensure initial button label/ARIA matches the current class
        setBtnState(btn, list.classList.contains('collapsed'));
      }
    });
  });

  window.toggleSection = function (button) {
    if (!button) return;
    // robustly find the sibling pub-list (skip text nodes safely)
    var list = button.previousElementSibling;
    if (!list || !list.classList.contains('pub-list')) {
      // fallback: search within parent
      list = button.parentElement && button.parentElement.querySelector('.pub-list');
    }
    if (!list) return;

    list.classList.toggle('collapsed');
    setBtnState(button, list.classList.contains('collapsed'));
  };
})();
</script>
