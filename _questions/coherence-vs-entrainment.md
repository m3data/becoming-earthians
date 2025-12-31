---
title: What is the difference between coherence and entrainment?
slug: coherence-vs-entrainment
summary: Two coordination regimes with profoundly different failure modes — and why the instinct to synchronise harder under stress is precisely wrong.
icon: ph-waves
related_methods:
  - agent-based-modeling
  - relational-sensing
related_projects:
  - entrainment-coherence-abm
  - semantic-climate
---

## The question

Coordination requires coupling — some way for parts to influence each other. But not all coupling is the same.

**Entrainment** is phase-locking toward a shared attractor. Think of pendulum clocks on the same wall synchronising their swings. Think of crowds falling into step. Think of organisations aligning around a single strategy.

**Coherence** is something different: the capacity to maintain integrity while absorbing perturbation. It does not require agreement. It requires relationship — ongoing mutual influence that preserves difference rather than eliminating it.

The question is: *when does each regime serve adaptive capacity, and when does it undermine it?*

<figure class="diagram">
  <img src="{{ '/assets/images/diagrams/entrainment-vs-coherence.svg' | relative_url }}" alt="Entrainment vs Coherence diagram — entrainment shows uniform alignment, coherence shows diverse orientations with connections">
</figure>

## Why it matters

The instinct under stress is to synchronise. Align. Get everyone on the same page. Eliminate variance. This instinct is precisely what produces brittle systems.

<div class="scale-progression">
  <div class="scale-item">
    <span class="scale-label">Individual</span>
    <div class="scale-content">
      <p>You're overwhelmed, so you try to match everyone else's pace. You suppress your own rhythms — the need for silence, for movement, for a different kind of attention. You abandon the practices that keep you grounded because they don't fit the group tempo. You burn out, and lose access to exactly the capacities you needed most.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Group</span>
    <div class="scale-content">
      <p>A project team under deadline pressure all adopts the same frantic pace. The person who works differently — who needs quiet focus, or who sees a flaw others are ignoring — bears the cost of staying in sync. They burn out first, and the team loses exactly the perspective it needed.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Organisation</span>
    <div class="scale-content">
      <p>A company mandates a single methodology across all departments. Teams that don't fit the mould spend more energy conforming than producing. When market conditions shift, no one has practiced adapting — everyone was locked to the same approach.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Community</span>
    <div class="scale-content">
      <p>A neighbourhood association pushes for unanimous agreement on every decision. Dissenters stop showing up. The remaining group becomes an echo chamber, blind to problems that the dissenters saw coming.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Society</span>
    <div class="scale-content">
      <p>Media ecosystems optimise for viral consensus. Nuanced voices can't compete with simplified takes. Public discourse loses the diversity of perspective needed to navigate complex challenges.</p>
    </div>
  </div>
  <div class="scale-item">
    <span class="scale-label">Civilisation</span>
    <div class="scale-content">
      <p>Global institutions converge on the same economic model, the same metrics of success, the same development pathway. When that model encounters limits — ecological, social, financial — there are no alternatives ready. The system has no fallback.</p>
    </div>
  </div>
</div>

Coherence offers an alternative: people and groups maintain their own reference points — identity, place, practice — while staying in relationship. When pressure mounts, they can step back, recover, and re-engage. The system survives because it never eliminated its own relief valves.

## The mechanism

```
Agent configuration
├── Some agents are load-bearing (high coupling + far from consensus)
├── Load-bearing agents bear disproportionate stabilisation work (1.6–2×)
│
├── If MANY load-bearers: burden distributed → each survives
├── If FEW load-bearers: each overloaded → fatigue accumulates
│
├── [ENTRAINMENT] No relief pathway → exhaustion → cascade failure
└── [COHERENCE]   Relief pathway (identity-pull) → recovery → stability
```

## Design implications

This finding has practical implications for any system that must absorb stress:

> Do the load-bearing members have independent recovery pathways?

If not, the system has cascade risk — regardless of how aligned or efficient it appears under normal conditions.

This reframes debates about consensus, diversity, and coordination. The goal is to ensure coupling preserves the escape valves that prevent exhaustion spirals.

## Related work

- [Adaptive capacity]({{ '/questions/adaptive-capacity/' | relative_url }}) — the broader context
- [Entrainment-Coherence ABM]({{ '/projects/entrainment-coherence-abm/' | relative_url }}) — the model
- [Relational sensing]({{ '/methods/relational-sensing/' | relative_url }}) — detecting these patterns in living systems
