---
name: consulting-os-kpi-architecture
description: Design the measurement system for a strategy or transformation — a driver-linked KPI tree, leading and lagging indicators, targets, owners, and dashboards. Use whenever the user mentions KPIs, metrics, measurement, scorecards, dashboards, OKRs, "how do we know it's working", performance management design, or target-setting. Skill 17 of the consulting suite.
version: 1.0.0
title: "Kpi Architecture"
status: active
---

# KPI Architecture

Organisations manage what they measure, and mis-manage what they mis-measure. This skill builds a small, driver-linked KPI system: every metric traces to the strategy, every metric has an owner who can move it, and leading indicators outnumber trophies.

## Method

**1. Derive the tree from the value drivers, top-down.** Start from the outcome the strategy promises (profit growth, share, valuation) and decompose through the driver logic — the same driver tree the business case used. Each strategic initiative should be visible somewhere in the tree; a strategy element with no metric is unmanaged, and a metric with no strategy link is decoration.

**2. Balance leading and lagging.** Lagging metrics (revenue, margin, churn) prove outcomes; leading metrics (pipeline coverage, adoption rate, cycle time, quality of input) predict them while there is still time to act. Each lagging KPI gets at least one leading counterpart with a hypothesised causal link — and that link is stated, so it can be checked against data later.

**3. Specify each KPI properly.** One line each: precise definition and formula, data source and refresh frequency, owner (a person who can influence it), target with the basis for the target (baseline, benchmark, or model — targets pulled from air corrupt the system), and thresholds for green/amber/red.

**4. Design against gaming.** For each KPI ask: how would a rational person hit this number while missing the point? Pair vulnerable metrics with a counter-metric (speed with quality, growth with margin, utilisation with satisfaction). Goodhart's law is a design constraint, not trivia.

**5. Keep it small and tiered.** Board sees 5–8; executive team 10–15; each function its own driver slice. Every metric that survives must answer: what decision changes when this moves? If nothing changes, cut it.

**6. Set the operating rhythm.** Who reviews what, at what cadence, with what escalation. A KPI system without a review ritual is a data warehouse.

Before drafting the final deliverable, load `references/deliverable.md` for the output template and quality bar.

## Hand-offs

Uses driver trees from **consulting-os-business-cases** (10) and the target state from **consulting-os-operating-model-design** (12). Absorbs tripwires from **consulting-os-assumption-audits** (03), risk triggers from **consulting-os-risk-mitigation** (15), and war-game signals from **consulting-os-war-gaming** (16). Powers the steering rhythm in **consulting-os-transformation-roadmaps** (14) and progress reporting in **consulting-os-board-memos** (20).
