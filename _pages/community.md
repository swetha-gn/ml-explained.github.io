---
layout: page
title: Community
permalink: /community/
---

<style>
  .community-wrap {
    display: grid;
    gap: 1rem;
  }

  .community-hero,
  .community-card {
    border-radius: 26px;
    border: 1px solid rgba(148, 163, 184, 0.18);
    background: rgba(15, 23, 42, 0.72);
    box-shadow: 0 18px 55px rgba(2, 8, 23, 0.16);
  }

  .community-hero {
    padding: clamp(1.5rem, 4vw, 3rem);
    color: #e5f0ff;
    background:
      radial-gradient(circle at 12% 18%, rgba(244, 114, 182, 0.20), transparent 26%),
      radial-gradient(circle at 88% 12%, rgba(56, 189, 248, 0.28), transparent 30%),
      linear-gradient(135deg, #07111f, #160a2f);
  }

  .community-hero h1 {
    margin: 0 0 1rem;
    color: white;
    font-size: clamp(2.3rem, 6vw, 4.6rem);
    line-height: 1;
    letter-spacing: -0.07em;
  }

  .community-hero p,
  .community-card p,
  .community-card li {
    color: #aebfd4;
  }

  .community-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 1rem;
  }

  .community-card {
    padding: 1.25rem;
  }

  .community-card h2,
  .community-card h3 {
    margin-top: 0;
    color: #f8fafc;
    letter-spacing: -0.04em;
  }

  .community-step {
    display: grid;
    grid-template-columns: 44px 1fr;
    gap: 0.8rem;
    align-items: start;
  }

  .community-number {
    display: grid;
    place-items: center;
    width: 44px;
    height: 44px;
    border-radius: 14px;
    color: white;
    background: linear-gradient(135deg, #38bdf8, #7c3aed);
    font-weight: 900;
  }

  @media (max-width: 860px) {
    .community-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="community-wrap">
  <section class="community-hero">
    <h1>A forum-style home for technical readers.</h1>
    <p>
      WaveGuide can grow beyond a portfolio and blog into a focused community for readers who want to discuss AI systems, research papers, photonics, GPU programming, deployment tradeoffs, and practical engineering lessons.
    </p>
  </section>

  <section class="community-grid">
    <article class="community-card">
      <h3>Discuss posts</h3>
      <p>Every article can eventually have a discussion thread for questions, corrections, implementation notes, and follow-up resources.</p>
    </article>
    <article class="community-card">
      <h3>Request explainers</h3>
      <p>Readers can suggest papers, systems, or concepts they want explained visually and practically.</p>
    </article>
    <article class="community-card">
      <h3>Share resources</h3>
      <p>A lightweight place for datasets, papers, benchmarks, tools, and engineering references.</p>
    </article>
  </section>

  <section class="community-card">
    <h2>Recommended implementation path</h2>
    <div class="community-step">
      <div class="community-number">1</div>
      <div>
        <h3>Keep GitHub Pages for the site</h3>
        <p>GitHub Pages is a great home for the static portfolio, blog, project pages, and visual UI.</p>
      </div>
    </div>
    <div class="community-step">
      <div class="community-number">2</div>
      <div>
        <h3>Use GitHub Discussions as the forum backend</h3>
        <p>Discussions can handle user posts, categories, moderation, and identity through GitHub accounts without a custom database.</p>
      </div>
    </div>
    <div class="community-step">
      <div class="community-number">3</div>
      <div>
        <h3>Embed comments with giscus</h3>
        <p>giscus can connect each blog post to a GitHub Discussion, giving the site a community layer while keeping hosting simple.</p>
      </div>
    </div>
  </section>

  <section class="community-card">
    <h2>Future discussion categories</h2>
    <ul>
      <li>Paper explainer requests</li>
      <li>Physics-informed ML and digital twins</li>
      <li>CUDA, quantization, and hardware-aware inference</li>
      <li>RAG, deployment, and MLOps lessons</li>
      <li>Reader projects and technical questions</li>
    </ul>
  </section>
</div>
