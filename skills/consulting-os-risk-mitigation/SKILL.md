---
name: consulting-os-risk-mitigation
description: Identify, quantify, and mitigate the risks to a strategy, transformation, or major decision — with owners, triggers, and pre-agreed responses. Use whenever the user mentions risks, risk register, mitigation, contingency, "what could go wrong", downside protection, or when a plan or recommendation is heading to approval and needs its risk story. Skill 15 of the consulting suite.
version: 1.0.0
title: "Risk Mitigation"
status: active
---

# Risk & Mitigation

A risk register that lists twenty risks all marked "medium" with mitigation "monitor closely" is theatre. This skill produces a short register of the risks that actually threaten the outcome, quantified in the client's units, each with a named owner, a trigger, and a pre-agreed response.

## Method

**1. Generate risks from structure, not brainstorm alone.** Walk four sources:
- The assumption register (every load-bearing assumption is a risk in waiting).
- The dependency map (every hard dependency can slip).
- The stakeholder map (every opposed or lukewarm power-holder is a risk).
- External scan: regulatory, competitive, technology, macro. For AI-related work include model performance drift, data quality, vendor dependence, and regulatory exposure explicitly.

**2. Quantify in the client's units.** Impact in dollars, months, or share — not high/medium/low alone. Likelihood as a rough probability band with the reasoning. Expected exposure (impact × likelihood) ranks the register; but flag low-probability/ruinous risks separately, because expected value understates what can kill you.

**3. Choose a treatment per risk — deliberately.** Avoid (change the plan), Reduce (act to cut likelihood or impact), Transfer (contract, insure, share), Accept (with eyes open, stated by whom). "Monitor" is not a treatment; it is the absence of one. Every Reduce action gets a cost — mitigation that costs more than the exposure it removes is a bad trade, and saying so is part of the job.

**4. Set triggers and pre-agreed responses.** For accepted and reduced risks: the observable early signal, who watches it, and the response already agreed — decided calmly now, not in the panic later. This converts the register into an operating instrument.

**5. Assign single-name owners and a review rhythm.** Risks without owners are wishes. The register is reviewed on the programme cadence, with movement (new, escalated, retired) reported, not just re-stated.

Before drafting the final deliverable, load `references/deliverable.md` for the output template and quality bar.

## Hand-offs

Consumes **consulting-os-assumption-audits** (03) tripwires, **consulting-os-transformation-roadmaps** (14) dependencies, and **consulting-os-stakeholder-alignment** (18) opposition. Trigger signals join the dashboard in **consulting-os-kpi-architecture** (17). The top risks and treatments appear in **consulting-os-board-memos** (20).
