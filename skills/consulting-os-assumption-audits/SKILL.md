---
name: consulting-os-assumption-audits
description: Surface, stress-test, and monitor the assumptions underneath a strategy, model, plan, or recommendation. Use whenever the user asks "what are we assuming", wants a red-team review, a pre-mortem, sensitivity to assumptions, or before any major recommendation is finalised; also when a business case, forecast, or strategy document is about to go to a decision-maker. Skill 03 of the consulting suite.
version: 1.0.0
title: "Assumption Audits"
status: active
---

# Assumption Audits

Strategies rarely fail because the analysis was wrong; they fail because an unexamined assumption was. This skill makes assumptions explicit, ranks them by danger, tests the dangerous ones, and sets tripwires for the rest.

## Method

**1. Extract assumptions.** Read the plan, model, or recommendation and list every claim that is taken as true without A/B-grade evidence. Look especially for the quiet ones:
- Continuity assumptions ("current growth continues", "the regulator stays put", "key staff stay").
- Behavioural assumptions ("customers will switch", "competitors won't respond", "the org will adopt this").
- Capability assumptions ("we can build this", "data quality is sufficient").
- Definitional assumptions (market boundaries, segment definitions, what counts as "cost").

**2. Rank on two axes:** impact if wrong × likelihood of being wrong. The kill zone is high-impact/high-uncertainty. Plot all assumptions; name the top 3–5 "load-bearing" ones.

**3. Test load-bearing assumptions.** For each: what evidence exists now, what cheap test would raise confidence (interview, data pull, pilot, expert call), and what the recommendation becomes if the assumption fails. If a recommendation survives all its load-bearing assumptions failing, it was never really resting on them — re-examine.

**4. Set tripwires.** For assumptions that cannot be tested now, define the observable signal that would show them failing, who watches it, and the pre-agreed response. This converts an audit into an early-warning system.

**5. Run a pre-mortem when stakes justify it.** "It is 18 months on and this failed — write the history." Cluster the causes; most map back to the assumption list and validate the ranking.

Before drafting the final deliverable, load `references/deliverable.md` for the output template and quality bar.

## Hand-offs

Runs against outputs of any skill, but is mandatory before **consulting-os-business-cases** (10), **consulting-os-strategic-options** (08) conclusions, and **consulting-os-board-memos** (20). Tripwires feed **consulting-os-risk-mitigation** (15) and **consulting-os-kpi-architecture** (17).
