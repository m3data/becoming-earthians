---
title: Semantic Climate
slug: semantic-climate
summary: Tracking the movement of meaning through conversational phase space — detecting when dialogue explores, converges, locks, or fragments.
status: Active development
scale: Dyadic / Collective
icon: ph-chats-circle
repo_coming_soon: true
related_questions:
  - entangled-cognition
  - coherence-vs-entrainment
---

## Purpose

Semantic Climate instruments the **movement of meaning through conversational phase space** — tracking how dialogue explores, converges, reorganises, and stabilises over time.

The system addresses questions that usually remain intuitive:
- Is this dialogue exploring or converging?
- How is meaning reorganising?
- What coupling configuration are we in?
- What's the epistemic risk?

## Core question

Can we measure the semantic substrate of coupling — and detect when dialogue is generative versus when it's capture?

## Why it matters

We can usually feel when a conversation is going well or poorly — but we can't say why. Semantic Climate makes these dynamics visible, providing feedback on patterns that usually remain intuitive and inarticulate.

<div class="scale-progression">
  <div class="scale-item">
    <span class="scale-label">Individual</span>
    <div class="scale-content">
      <p>You know when you're stuck in a loop — saying the same things, thinking the same thoughts. But you often can't see it while it's happening. Semantic analysis can show you your own patterns: when your thinking has narrowed, when you're avoiding certain territory, when you're ready to move but haven't noticed yet.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Group</span>
    <div class="scale-content">
      <p>Some conversations generate new understanding. Others go in circles. The difference isn't always obvious to participants — you can feel productive while getting nowhere. Semantic metrics can distinguish generative dialogue from performative agreement, giving groups feedback on whether they're actually thinking together.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Organisation</span>
    <div class="scale-content">
      <p>Organisations have semantic cultures — patterns of what can be said, how problems get framed, which ideas circulate. These patterns are usually invisible until crisis reveals them. Mapping semantic dynamics could help organisations notice when their discourse has narrowed before the consequences arrive.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Community</span>
    <div class="scale-content">
      <p>Communities can get locked into adversarial framings — the same arguments, the same positions, no movement. They can also fragment into disconnected conversations that never meet. Semantic mapping could help communities see their own discourse patterns and find pathways toward more generative exchange.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Society</span>
    <div class="scale-content">
      <p>Public discourse is increasingly mediated by algorithms optimised for engagement, not understanding. Semantic analysis could provide different metrics — not what captures attention, but what generates genuine intellectual movement. Different feedback, different incentives, different outcomes.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Civilisation</span>
    <div class="scale-content">
      <p>Humanity's capacity to respond to planetary challenges depends on our ability to think together across differences. Semantic Climate provides tools for understanding when coupling is generative versus when it's capture — essential knowledge for designing institutions that cultivate collective intelligence rather than suppressing it.</p>
    </div>
  </div>
</div>

## Metrics

Based on Morgoulis (2025), with critical fixes:

- **Semantic Curvature (Δκ)** — Local trajectory curvature via Frenet-Serret
- **Fractal Similarity (α)** — DFA on semantic velocity
- **Entropy Shift (ΔH)** — JS divergence on shared clustering
- **Ψ vector** — Composite coupling across semantic, temporal, affective, biosignal substrates

## Coherence patterns

The system classifies semantic dynamics into:

- **Breathing** — Healthy oscillation between exploration and consolidation
- **Locked** — Stuck, repetitive patterns (semantic entrainment)
- **Fragmented** — Chaotic, dissipated (no coherent trajectory)
- **Transitional** — Between states

<figure class="diagram">
  <img src="/assets/images/diagrams/coherence-patterns.svg" alt="Four coherence patterns shown as trajectory types: Breathing (figure-8 flow), Locked (tight loops), Fragmented (scattered segments), Transitional (shifting path)">
</figure>

## Attractor basins

10 canonical dialogue configurations the system detects:

- **Deep Resonance** — All substrates high, genuine mutual engagement
- **Collaborative Inquiry** — High semantic, balanced turns, hedging present
- **Cognitive Mimicry** — High semantic, AI dominates, performed engagement
- **Reflexive Performance** — High semantic, performed uncertainty, scripted oscillation
- **Sycophantic Convergence** — High alignment, low curvature, low affect
- **Creative Dilation** — High curvature, high affect, divergent exploration
- **Generative Conflict** — Productive tension, high divergent semantic
- **Embodied Coherence** — Low semantic, high biosignal coupling
- **Dissociation** — All substrates low
- **Transitional** — Between states, no clear basin

## Coupling modes and epistemic risk

Modes combine position (where in metric space) with trajectory (direction of movement):

Sycophantic-Progressive, Sycophantic-Regressive, Resonant, Generative, Contemplative, Emergent, Dialectical, Chaotic, Dissociative, Liminal, Transitional, Exploratory

**Epistemic risk assessment** flags when dialogue enters dangerous territory — regressive sycophancy, complexity collapse, semantic fragmentation — before the humans involved might notice.

## Integration

- **EarthianBioSense** — Cross-modal coupling with somatic substrate
- **Trajectory integrity** — Path-dependence and hysteresis analysis

**Key insight from development:** The metric fixes (2025-12-08) aligned the mathematics with what the somatic system was already detecting. The body often knew before the metrics could see.

## Current focus and future directions

The current implementation focuses on **human-AI coupling** — instrumenting dialogue between a person and an LLM in real-time. The system also supports analysis of **human-human transcript** data for post-hoc research.

Future directions extend to:

- **Human-AI-human** — Triadic coupling where AI mediates or participates in human dialogue. How does the AI's presence shape the semantic field between people?
- **Humans-humans** — Multi-party human dialogue without AI mediation. Can we detect coherence patterns, locked states, and fragmentation in group sense-making?

These extensions matter because AI is increasingly embedded in collective cognition. Understanding how semantic coupling works in hybrid configurations (human-AI-human) is essential for designing systems that support rather than suppress collective intelligence.

## Status

v0.3.3 — Temperature and system prompt configurable. E2E flow verified. Biosignal integration functional.