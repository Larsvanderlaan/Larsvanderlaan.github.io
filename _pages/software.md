---
layout: page
permalink: /software/
title: software
description: Selected software and code accompanying my methodological work.
nav: true
nav_order: 2
---

This page highlights selected research software accompanying my work in causal inference, semiparametric statistics, and calibrated machine learning. Each package is tied to a methodological paper and is intended to make the underlying ideas easier to inspect, reproduce, and use.

<div class="software-list">
  <section class="software-item">
    <h2><a href="https://larsvanderlaan.github.io/causalCalibration/">causalCalibration</a></h2>
    <p>
      <code>causalCalibration</code> accompanies <em>Causal isotonic calibration for heterogeneous treatment effects</em>. It provides post-hoc calibration and cross-calibration for black-box heterogeneous treatment effect estimators, improving reliability while preserving the original learning pipeline.
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
      <code>hte3</code> accompanies <em>Combining T-learning and DR-learning: a framework for oracle-efficient estimation of causal contrasts</em>. It implements efficient plug-in learning for heterogeneous causal contrasts, including the conditional average treatment effect and conditional relative risk.
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
      <code>ppi-aipw</code> accompanies <em>Prediction-Powered Inference via Calibration</em>. It provides semisupervised mean inference with AIPW-style estimators and calibrated prediction scores for settings with limited labels and abundant unlabeled covariates.
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
      <code>calibratedDML</code> accompanies <em>Doubly robust inference via calibration</em>. It adds a calibration step to standard debiased machine learning pipelines for inference on linear functionals, with the goal of improving robustness and finite-sample performance.
    </p>
    <div class="software-links">
      <a href="https://arxiv.org/pdf/2411.02771">paper</a>
      <a href="https://larsvanderlaan.github.io/calibratedDML/index.html">package site</a>
      <a href="https://github.com/Larsvanderlaan/CDML">code</a>
    </div>
  </section>
</div>
