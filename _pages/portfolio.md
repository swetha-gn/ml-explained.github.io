---
layout: page
title: Portfolio
permalink: /portfolio/
---

<style>
  .portfolio-hero {
    padding: clamp(1.5rem, 4vw, 3rem);
    border-radius: 28px;
    color: #e5f0ff;
    background:
      radial-gradient(circle at 8% 12%, rgba(56, 189, 248, 0.28), transparent 28%),
      radial-gradient(circle at 88% 14%, rgba(167, 139, 250, 0.26), transparent 24%),
      linear-gradient(135deg, #07111f, #120b2f);
    border: 1px solid rgba(148, 163, 184, 0.18);
    box-shadow: 0 24px 70px rgba(2, 8, 23, 0.26);
  }

  .portfolio-hero h1 {
    margin: 0 0 1rem;
    color: white;
    font-size: clamp(2.4rem, 6vw, 4.8rem);
    line-height: 0.98;
    letter-spacing: -0.07em;
  }

  .portfolio-hero p {
    max-width: 820px;
    color: #cbd5e1;
    font-size: 1.1rem;
    line-height: 1.7;
  }

  .portfolio-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
    margin-top: 1.4rem;
  }

  .portfolio-card {
    padding: 1.25rem;
    border-radius: 22px;
    border: 1px solid rgba(148, 163, 184, 0.18);
    background: rgba(15, 23, 42, 0.72);
    box-shadow: 0 16px 45px rgba(2, 8, 23, 0.16);
  }

  .portfolio-card h2,
  .portfolio-card h3 {
    margin-top: 0;
    color: #f8fafc;
    letter-spacing: -0.04em;
  }

  .portfolio-card p,
  .portfolio-card li {
    color: #aebfd4;
  }

  .portfolio-highlight {
    color: #7dd3fc;
    font-weight: 800;
  }

  .portfolio-chip-row {
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem;
    margin-top: 0.85rem;
  }

  .portfolio-chip {
    border-radius: 999px;
    padding: 0.34rem 0.62rem;
    color: #dbeafe;
    background: rgba(14, 165, 233, 0.12);
    border: 1px solid rgba(125, 211, 252, 0.22);
    font-size: 0.82rem;
  }

  .portfolio-timeline {
    display: grid;
    gap: 0.85rem;
  }

  .portfolio-role {
    padding-left: 1rem;
    border-left: 3px solid rgba(56, 189, 248, 0.55);
  }

  .portfolio-role strong {
    color: #f8fafc;
  }

  .portfolio-role span {
    display: block;
    color: #93c5fd;
    font-weight: 700;
  }

  @media (max-width: 760px) {
    .portfolio-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<section class="portfolio-hero">
  <h1>Portfolio for applied AI, photonics, and systems engineering.</h1>
  <p>
    I’m Swetha Gendlur Nagarajan, an MS Applied Data Science student at the University of Florida with a 4.0 GPA, graduating in May 2026. My work focuses on making expensive computation accessible: physics-informed models, GPU acceleration, RAG systems, and deployment paths that fit real engineering workflows.
  </p>
</section>

<div class="portfolio-grid">
  <article class="portfolio-card">
    <h2>Education</h2>
    <p><strong>University of Florida</strong> — MS Applied Data Science, GPA 4.0, expected May 2026.</p>
    <p><strong>PSG College of Technology</strong> — BE Computer Science and Engineering, GPA 8.76/10.</p>
  </article>

  <article class="portfolio-card">
    <h2>Publication</h2>
    <p><strong>First-author peer-reviewed paper, SPIE Photonics West 2026</strong></p>
    <p>“From ML to Physics-Informed Neural Networks: Scalable Digital Twin for Stress-Aware Design in Photonic Structures.”</p>
  </article>
</div>

<h2>Selected projects and impact</h2>

<div class="portfolio-grid">
  <article class="portfolio-card">
    <h3>Stress-aware digital twin for photonic structures</h3>
    <p><span class="portfolio-highlight">8,344× speedup</span> with <span class="portfolio-highlight">R²=0.9999</span>, deployed through ONNX inside FLOOPS.</p>
    <div class="portfolio-chip-row"><span class="portfolio-chip">PhysicsNeMo</span><span class="portfolio-chip">PINNs</span><span class="portfolio-chip">ONNX Runtime</span></div>
  </article>

  <article class="portfolio-card">
    <h3>Healthcare RAG system at Optum</h3>
    <p>Served retrieval over <span class="portfolio-highlight">12M records</span> with <span class="portfolio-highlight">95% accuracy</span> and <span class="portfolio-highlight">40% faster retrieval</span>.</p>
    <div class="portfolio-chip-row"><span class="portfolio-chip">RAG</span><span class="portfolio-chip">Apache Spark</span><span class="portfolio-chip">Azure</span></div>
  </article>

  <article class="portfolio-card">
    <h3>CUDA batch inference acceleration</h3>
    <p>Built an optimized inference path using INT8/INT6 quantization and GPU execution, reaching a <span class="portfolio-highlight">1,932× speedup</span>.</p>
    <div class="portfolio-chip-row"><span class="portfolio-chip">CUDA</span><span class="portfolio-chip">C/C++</span><span class="portfolio-chip">Quantization</span></div>
  </article>

  <article class="portfolio-card">
    <h3>IIT Madras Research Park ML infrastructure</h3>
    <p>Delivered <span class="portfolio-highlight">95% detection accuracy</span> and an <span class="portfolio-highlight">18% improvement</span> over baseline.</p>
    <div class="portfolio-chip-row"><span class="portfolio-chip">ML Infrastructure</span><span class="portfolio-chip">Python</span><span class="portfolio-chip">Detection</span></div>
  </article>
</div>

<h2>Experience</h2>

<div class="portfolio-card portfolio-timeline">
  <div class="portfolio-role"><span>Aug 2024–Present</span><strong>Graduate Research Assistant, Florida Semiconductor Institute, University of Florida — NVIDIA Partnership</strong></div>
  <div class="portfolio-role"><span>Aug–Dec 2025</span><strong>ML Developer, LiteSeeker Solutions</strong></div>
  <div class="portfolio-role"><span>Jan–Jul 2024</span><strong>Machine Learning Engineer, Optum Global Solutions</strong></div>
  <div class="portfolio-role"><span>Jul–Dec 2023</span><strong>ML Infrastructure Intern, IIT Madras Research Park</strong></div>
</div>

<h2>Technical toolkit</h2>

<div class="portfolio-card">
  <div class="portfolio-chip-row">
    <span class="portfolio-chip">CUDA</span>
    <span class="portfolio-chip">PyTorch</span>
    <span class="portfolio-chip">PhysicsNeMo</span>
    <span class="portfolio-chip">ONNX Runtime</span>
    <span class="portfolio-chip">Docker</span>
    <span class="portfolio-chip">Kubernetes</span>
    <span class="portfolio-chip">Azure</span>
    <span class="portfolio-chip">FastAPI</span>
    <span class="portfolio-chip">Apache Spark</span>
    <span class="portfolio-chip">C/C++</span>
    <span class="portfolio-chip">Python</span>
  </div>
</div>
