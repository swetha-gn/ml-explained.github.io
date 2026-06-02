---
layout: waveguide
title: Blog
permalink: /blog/
nav: blog
---

<section class="wg-section">
  <h1 class="wg-page-title">Blog</h1>
  <p class="wg-page-subtitle">Scrollable notes on ML, scientific AI, papers, photonics, chips, and deployment. Categories can grow naturally as the writing grows.</p>
</section>

<div class="wg-rule"></div>

<section class="wg-section">
  <div class="wg-section__head">
    <div>
      <p class="wg-kicker">Categories</p>
      <h2>Browse topics</h2>
    </div>
    <a class="wg-link" href="{{ '/categories/' | relative_url }}">category archive →</a>
  </div>
  <div class="wg-chip-row">
    {% assign categories = site.categories | sort %}
    {% for category in categories %}
      <a class="wg-chip" href="{{ '/categories/' | relative_url }}">{{ category[0] }}</a>
    {% endfor %}
    <span class="wg-chip">Future: Scientific AI</span>
    <span class="wg-chip">Future: Deployment</span>
  </div>
</section>

<section class="wg-section">
  <div class="wg-section__head">
    <div>
      <p class="wg-kicker">All posts</p>
      <h2>Scroll and choose</h2>
    </div>
  </div>
  <div class="wg-blog-list">
    {% for post in site.posts %}
      <article class="wg-post">
        <div>
          <p class="wg-meta">{{ post.date | date: "%b %-d, %Y" }}{% if post.categories.size > 0 %} · {{ post.categories | join: ', ' }}{% endif %}</p>
          <h2><a class="wg-link" href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
          <p>{{ post.excerpt | strip_html | truncate: 220 }}</p>
          <div class="wg-chip-row">
            {% for tag in post.tags limit:5 %}<span class="wg-chip">{{ tag }}</span>{% endfor %}
          </div>
        </div>
        <div class="wg-post__thumb" aria-hidden="true"></div>
      </article>
    {% endfor %}
  </div>
</section>
