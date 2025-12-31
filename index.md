---
layout: default
title: Home
---

<div class="home">
  <section class="hero">
    <div class="hero-image">
      <img src="{{ '/assets/images/earth-blue-marble.jpg' | relative_url }}" alt="Earth from space — NASA Blue Marble">
    </div>
    <div class="hero-content">
      <h1>{{ site.title }}</h1>
      <p class="subtitle">{{ site.subtitle }}</p>
    </div>
  </section>

  <section class="home-intro">
    <p>A portal into an ongoing inquiry.</p>
    <p>The central question:</p>
    <blockquote>
      How can humanity cultivate adaptive capacity commensurate with the scale, speed, and entanglement of contemporary crises — without collapsing into uniformity, control, or fragmentation?
    </blockquote>
  </section>

  <section class="home-entry-points">
    <h2>You might enter here if you're interested in...</h2>
    <ul class="entry-points">
      <li>
        <a href="{{ '/questions/adaptive-capacity/' | relative_url }}">
          <strong>Adaptive capacity</strong>
          <span>How collective systems maintain integrity under stress</span>
        </a>
      </li>
      <li>
        <a href="{{ '/questions/coherence-vs-entrainment/' | relative_url }}">
          <strong>Coherence vs entrainment</strong>
          <span>Why synchronisation fails and what works instead</span>
        </a>
      </li>
      <li>
        <a href="{{ '/questions/entangled-cognition/' | relative_url }}">
          <strong>Entangled cognition</strong>
          <span>How meaning emerges through relationship</span>
        </a>
      </li>
      <li>
        <a href="{{ '/methods/' | relative_url }}">
          <strong>Sensing and modeling</strong>
          <span>Instruments for detecting coherence in living systems</span>
        </a>
      </li>
      <li>
        <a href="{{ '/projects/' | relative_url }}">
          <strong>Projects</strong>
          <span>Concrete probes into these questions</span>
        </a>
      </li>
    </ul>
  </section>
</div>
