---
title: Agent-based modeling
slug: agent-based-modeling
summary: Exploring mechanism through simulation — testing how local rules produce emergent collective dynamics.
icon: ph-grid-nine
related_questions:
  - adaptive-capacity
  - coherence-vs-entrainment
---

## What this method is for

Agent-based modeling (ABM) creates populations of agents with simple rules and observes what emerges from their interaction. It is a method for **mechanism discovery** — understanding *how* collective patterns arise from local dynamics.

ABM is particularly suited to questions about:

- Emergence — how macro patterns arise from micro interactions
- Heterogeneity — how diversity affects collective outcomes
- Thresholds — where regime changes occur
- Feedback — how local and global dynamics couple

## What it can tell us

ABM can identify **sufficient conditions** for phenomena. If a model produces cascade failure when load-bearing agents lack relief pathways, this demonstrates that the mechanism is *capable* of producing the effect — not that it is the only cause in real systems.

ABM is a **conceptual instrument** — a sandbox for testing ideas, not a predictive simulator of specific real-world systems.

## What it cannot tell us

ABM cannot:

- Prove that a mechanism operates in any particular real system
- Predict specific outcomes in complex real-world contexts
- Replace empirical observation or fielded practice

The relationship between model and world is always interpretive. Models generate insight, not truth. The map is not the territory.

## Why it is appropriate for this inquiry

The coherence vs entrainment question is fundamentally about **mechanism**: what structural features of coordination regimes produce different failure modes under stress?

ABM allows controlled experiments impossible in real collectives — systematically varying parameters, running thousands of replicates, tracking agent-level dynamics at high resolution.

We've run 600+ experimental runs using NetLogo BehaviorSpace testing the Coherence Theorem, identifying that relief pathways (not diversity per se) are the causal mechanism preventing cascade failure.

## Tools

- **NetLogo** — Visual, accessible ABM environment
- **BehaviorSpace** — Systematic experiment running
- **Python/Jupyter** — Statistical analysis of exports
