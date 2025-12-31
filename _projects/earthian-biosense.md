---
title: EarthianBioSense
slug: earthian-biosense
summary: Biosignal acquisition distinguishing entrainment (breath-heart coupling) from coherence (trajectory integrity) in living systems. Currently focused on human physiology and integration with Semantic Climate.
status: Active development
scale: Individual / Dyadic
icon: ph-heartbeat
repo_coming_soon: true
related_questions:
  - entangled-cognition
  - coherence-vs-entrainment
---

## Purpose

EarthianBioSense provides instruments for sensing the difference between **entrainment** and **coherence** in living systems (currently focused on humans) — a distinction that emerged through empirical work with this tool.

**Entrainment** is breath-heart phase coupling — the local grip, the synchronisation between respiratory and cardiac rhythms. **Coherence** is trajectory integrity over time — the global journey, the capacity to maintain identity while moving through state space.

These are not the same thing. Meditation sessions show high coherence (0.55) with low entrainment; rhythmic activity shows high entrainment (0.50+) with lower coherence. The relationship inverts depending on what the nervous system is doing.

<figure class="diagram">
  <img src="/assets/images/diagrams/entrainment-coherence-axes.svg" alt="Two-axis plot showing entrainment vs coherence: meditation in upper-left (high coherence, low entrainment), rhythmic activity in lower-right (high entrainment, lower coherence)">
</figure>

## Core question

How can we sense the difference between entrainment and coherence in living systems — and what does each tell us about adaptive capacity?

## What it does

- **iOS capture app** — Records HRV and inter-beat intervals during sessions
- **Python pipeline** — Computes phase dynamics, entrainment metrics, trajectory analysis
- **Breath-heart coupling detection** — Measures phase-locking between respiratory and cardiac rhythms
- **Mode classification** — Breathing, locked, fragmented, transitional (describes trajectory patterns, not states)

## Why it matters

Our bodies know things before our minds do. Your heart rate shifts when a conversation turns tense. Your breathing synchronises with someone you trust. These signals are usually invisible — but they're not inaccessible.

<div class="scale-progression">
  <div class="scale-item">
    <span class="scale-label">Individual</span>
    <div class="scale-content">
      <p>You feel anxious but can't say why. Your chest is tight, your breathing shallow, but nothing obvious triggered it. Your body is responding to something your conscious mind hasn't registered. Biosensing makes this visible — giving you data on your own nervous system state, so you can notice dysregulation before it becomes distress.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Group</span>
    <div class="scale-content">
      <p>In a difficult meeting, you can feel when the room shifts — when someone shuts down, when conflict goes underground, when genuine alignment emerges. These felt senses have physiological correlates. Biosensing makes the invisible visible, giving groups feedback on dynamics they can usually only intuit.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Organisation</span>
    <div class="scale-content">
      <p>Burnout cascades are biological events, not just psychological ones. When load concentrates on certain people, their nervous systems show it before productivity metrics do. Early detection through biosensing could prevent the exhaustion spirals that collapse teams.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Community</span>
    <div class="scale-content">
      <p>Collective trauma, chronic stress, and social fragmentation show up in bodies. A community under sustained pressure has different physiological signatures than one that feels safe. Sensing these patterns could inform interventions — not by surveillance, but by giving communities mirrors for their own collective state.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Society</span>
    <div class="scale-content">
      <p>Public health already tracks population-level biosignals — heart disease rates, sleep patterns, stress hormones. But these are lagging indicators, measured after damage is done. Real-time biosensing could provide early warning systems for collective dysregulation.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Civilisation</span>
    <div class="scale-content">
      <p>If coherence and entrainment are real dynamics — not just metaphors — they should be detectable in living systems. Biosensing lets us test whether the patterns we model in simulation actually show up in human collectives. It connects abstract theory to embodied reality.</p>
    </div>
  </div>
</div>

## Integration

Designed to work with:

- **Semantic Climate** — Cross-modal coupling between somatic and semantic substrates
- **EECP** — Protocol instrumentation for collective practice

## Status

iOS capture app v0.1 complete. v0.2 spec ready (real-time processing, self-reflection feedback). Python processing pipeline functional with movement-preserving classification. Integration with Semantic Climate verified.