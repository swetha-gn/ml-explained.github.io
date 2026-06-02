---
layout: page
title: Portfolio
permalink: /portfolio/
icon: fas fa-briefcase
order: 2
---

<link rel="stylesheet" href="{{ '/assets/css/waveguide.css' | relative_url }}">

<div class="waveguide-page wg-shell">
  <section class="wg-panel">
    <p class="wg-eyebrow">Portfolio</p>
    <h1>Projects at the intersection of ML, physical systems, and deployment.</h1>
    <p class="wg-lede">
      This page is the starting point for deeper case studies: what I built, why it mattered,
      what constraints shaped the solution, and what the final system achieved.
    </p>
  </section>

  <section class="wg-panel">
    <div class="wg-section-head">
      <div>
        <p class="wg-eyebrow">Selected work</p>
        <h2>Case-study pipeline</h2>
      </div>
      <a href="{{ '/about/' | relative_url }}">More about me →</a>
    </div>
    <div class="wg-post-grid">
      <article class="wg-card wg-card--accent">
        <p class="wg-card__meta">Research · Photonics</p>
        <h3>Stress-aware photonic digital twin</h3>
        <p>Physics-informed surrogate modeling for scalable stress-aware design in photonic structures.</p>
        <div class="wg-tags">
          <span>PINNs</span>
          <span>Digital twins</span>
          <span>ONNX</span>
        </div>
      </article>
      <article class="wg-card">
        <p class="wg-card__meta">Applied AI · Healthcare</p>
        <h3>Healthcare retrieval systems</h3>
        <p>RAG workflows over large healthcare datasets, focused on retrieval quality and practical latency improvements.</p>
        <div class="wg-tags">
          <span>RAG</span>
          <span>Search</span>
          <span>Evaluation</span>
        </div>
      </article>
      <article class="wg-card">
        <p class="wg-card__meta">Systems · Acceleration</p>
        <h3>CUDA batch inference</h3>
        <p>Hardware-aware inference, quantization, and deployment notes for real-world model speedups.</p>
        <div class="wg-tags">
          <span>CUDA</span>
          <span>INT8</span>
          <span>MLOps</span>
        </div>
      </article>
    </div>
  </section>

  <section class="wg-panel">
    <p class="wg-eyebrow">Impact snapshot</p>
    <h2>Metrics to expand into detailed stories</h2>
    <div class="wg-metric-grid">
      <div class="wg-stat">
        <span>Digital twin</span>
        <strong>8,344×</strong>
        <p>Reported surrogate speedup for stress-aware photonic design.</p>
      </div>
      <div class="wg-stat">
        <span>Model fit</span>
        <strong>R² 0.9999</strong>
        <p>High-fidelity prediction target for the photonics surrogate story.</p>
      </div>
      <div class="wg-stat">
        <span>Inference</span>
        <strong>1,932×</strong>
        <p>CUDA batch inference acceleration to document with system context.</p>
      </div>
    </div>
  </section>
</div>
