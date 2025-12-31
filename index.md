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
    <p>This site is a portal into an ongoing inquiry.</p>
    <p>Guided by a central question:</p>
    <blockquote>
      How can humanity cultivate adaptive capacity commensurate with the scale, speed, and entanglement of contemporary crises — without collapsing into uniformity, control, or fragmentation?
    </blockquote>
    <p>Humanity’s current adaptive mechanisms are mismatched with the scale and speed of contemporary crises, leading to systemic fatigue, entrainment pressures, and loss of diversity.</p>
  </section>

  <section class="home-entry-points">
    <h2>You might explore based on your interests...</h2>

    <h3 class="entry-category">Core inquiries</h3>
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
    </ul>

    <h3 class="entry-category">Tools & perspectives</h3>
    <ul class="entry-points">
      <li>
        <a href="{{ '/methods/' | relative_url }}">
          <strong>Sensing and modeling</strong>
          <span>Instruments for detecting coherence in living systems</span>
        </a>
      </li>
    </ul>

    <h3 class="entry-category">Concrete work</h3>
    <ul class="entry-points">
      <li>
        <a href="{{ '/projects/' | relative_url }}">
          <strong>Projects</strong>
          <span>Probes into these questions — biosensing, semantic analysis, simulation</span>
        </a>
      </li>
    </ul>
  </section>
</div>
