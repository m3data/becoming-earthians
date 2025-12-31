---
title: Entrainment-Coherence ABM
slug: entrainment-coherence-abm
summary: Agent-based-model using Netlogo for testing how collective systems maintain adaptive capacity under stress.
status: Active research
scale: Collective
icon: ph-graph
repo: https://github.com/m3data/entrainment-coherence-abm
related_questions:
  - adaptive-capacity
  - coherence-vs-entrainment
---

## Purpose

This NetLogo model tests the **Coherence Theorem**:

> In agent-based systems with heterogeneous identity and bounded coupling, regimes that preserve internal diversity will exhibit lower peak disruption and faster recovery under repeated perturbation than regimes optimised for phase alignment.

## Core question

What distinguishes coordination regimes that survive stress from those that cascade into failure?

<figure class="diagram">
  <img src="{{ '/assets/images/diagrams/abm-stress-response.svg' | relative_url }}" alt="ABM stress response diagram showing entrainment failing to recover while coherence returns to baseline">
</figure>

## Why it matters

Models let us test claims we can't ethically experiment with in the real world. We can't deliberately stress organisations to see which coordination styles fail. But we can simulate these dynamics and discover principles that transfer.

<div class="scale-progression">
  <div class="scale-item">
    <span class="scale-label">Individual</span>
    <div class="scale-content">
      <p>You've felt the cost of trying to stay in sync with people whose pace doesn't match yours. The model shows why: synchronisation isn't free. Someone pays the coordination tax. Understanding this can help you notice when you're bearing disproportionate load — and make different choices.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Group</span>
    <div class="scale-content">
      <p>Teams often double down on alignment when stress increases — more meetings, tighter coordination, less tolerance for deviation. The model shows this is precisely backward. The groups that survive are those that preserve escape valves — ways for people to step back and recover without leaving entirely.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Organisation</span>
    <div class="scale-content">
      <p>Management science optimises for efficiency — reducing variance, standardising process, eliminating slack. The model shows why this creates fragility: load concentrates on whoever doesn't fit the standard, and when they break, the system cascades. Resilient organisations need deliberate relief pathways.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Community</span>
    <div class="scale-content">
      <p>Community organising often pressures toward consensus — unanimous agreement as a sign of health. The model suggests this is a trap. Communities that suppress dissent lose their early warning systems. The people who leave first are often the ones who saw what was coming.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Society</span>
    <div class="scale-content">
      <p>Political polarisation looks like fragmentation, but it's often entrainment — everyone locked to their pole with no independent recovery pathway. The model shows why "reaching across the aisle" fails if there's no space to step back first. You can't re-couple from exhaustion.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Civilisation</span>
    <div class="scale-content">
      <p>Global coordination on existential risks requires coupling — but what kind? The model suggests that top-down synchronisation will collapse under stress, leaving us worse off than distributed approaches that preserve local autonomy. The path to planetary coordination may run through protecting diversity, not eliminating it.</p>
    </div>
  </div>
</div>

## Key findings

The model identifies a specific mechanism: **load concentration without relief pathways leads to cascade failure.**

When systems coordinate through phase-locking (entrainment), certain agents — those most socially sensitive and most different from consensus — bear disproportionate cost to stabilise the collective. If these load-bearing agents lack independent recovery pathways, they exhaust themselves and trigger cascade failure.

Systems that preserve individual reference points (coherence) provide relief pathways that prevent this cascade.

### Effect sizes

| Comparison | Effect Size |
|------------|-------------|
| Recovery time ratio at high stress | 12× longer (entrainment vs coherence) |
| Peak deviation ratio at high stress | 4× higher (entrainment vs coherence) |
| Recovery cost under periodic stress | 30× higher (entrainment vs coherence) |

## Design invariant

> Systems that rely on continuous synchronisation must provide independent recovery pathways for high-load agents, or they will externalise collapse risk onto a shrinking subset of stabilisers.

## Status

14 experiments completed (~600 runs). Core mechanism identified. Ready for extension to multi-scale and network topology variants.