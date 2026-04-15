---
layout: page
permalink: /software/
title: software
description: Selected software and code accompanying my methodological work.
nav: true
nav_order: 2
---

This page collects software accompanying some of my recent work in causal inference, semiparametric statistics, and calibrated machine learning. The focus is on lightweight research software: each package implements a specific methodological contribution and links directly to the corresponding paper.

<div class="software-list">
  <section class="software-item">
    <h2><a href="https://larsvanderlaan.github.io/causalCalibration/">causalCalibration</a></h2>
    <p>
      An R package implementing causal isotonic calibration and cross-calibration for heterogeneous treatment effect predictors. It wraps black-box CATE learners with post-hoc calibration procedures that improve reliability while preserving the original prediction pipeline.
    </p>
    <div class="software-links">
      <a href="https://proceedings.mlr.press/v202/van-der-laan23a/van-der-laan23a.pdf">paper</a>
      <a href="https://larsvanderlaan.github.io/causalCalibration/">package site</a>
      <a href="https://github.com/Larsvanderlaan/causalCalibration">code</a>
    </div>
  </section>

  <section class="software-item">
    <h2><a href="https://larsvanderlaan.github.io/hte3/">hte3</a></h2>
    <p>
      An R package for efficient plug-in learning of heterogeneous causal contrasts, including the conditional average treatment effect and conditional relative risk. It implements stable, oracle-efficient alternatives to standard DR- and R-learning style workflows.
    </p>
    <div class="software-links">
      <a href="https://arxiv.org/pdf/2402.01972.pdf">paper</a>
      <a href="https://larsvanderlaan.github.io/hte3/">package site</a>
      <a href="https://github.com/Larsvanderlaan/hte3">code</a>
    </div>
  </section>

  <section class="software-item">
    <h2><a href="https://github.com/Larsvanderlaan/ppi-aipw">ppi-aipw</a></h2>
    <p>
      A Python package for prediction-powered and semisupervised mean inference with AIPW-style estimators and post-hoc calibration. It is designed for settings with limited labels, abundant unlabeled covariates, and potentially miscalibrated prediction scores.
    </p>
    <div class="software-links">
      <a href="https://larsvanderlaan.github.io/ppi-aipw/paper.pdf">paper</a>
      <a href="https://larsvanderlaan.github.io/ppi-aipw/">package site</a>
      <a href="https://github.com/Larsvanderlaan/ppi-aipw">code</a>
    </div>
  </section>

  <section class="software-item">
    <h2><a href="https://larsvanderlaan.github.io/calibratedDML/index.html">calibratedDML</a></h2>
    <p>
      An R package implementing calibrated debiased machine learning for doubly robust inference on linear functionals. The package adds a simple calibration step to standard DML pipelines to improve robustness and finite-sample performance.
    </p>
    <div class="software-links">
      <a href="https://arxiv.org/pdf/2411.02771">paper</a>
      <a href="https://larsvanderlaan.github.io/calibratedDML/index.html">package site</a>
      <a href="https://github.com/Larsvanderlaan/CDML">code</a>
    </div>
  </section>
</div>
