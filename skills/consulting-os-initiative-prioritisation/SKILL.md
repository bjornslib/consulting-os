---
name: consulting-os-initiative-prioritisation
description: Prioritise a set of initiatives, projects, or use cases against value, feasibility, and capacity — producing a sequenced, funded list and an explicit not-doing list. Use whenever the user mentions prioritisation, ranking initiatives, use-case selection (including AI use cases), roadmap ordering, "we can't do everything", capacity allocation, or value-vs-effort decisions. Skill 13 of the consulting suite.
version: 1.0.0
title: "Initiative Prioritisation"
status: active
---

# Initiative Prioritisation

Prioritisation only happened if something was killed. This skill scores initiatives honestly, respects real capacity constraints, sequences by dependency and learning value — and produces a not-doing list with names on it.

## Method

**1. Normalise the initiative list.** One card per initiative: outcome sought, rough value ($ or strategic, stated in the same units across cards), cost, duration, owner, dependencies, and confidence grade on the estimates. Initiatives sized on different assumptions cannot be compared — normalise first.

**2. Score on value × feasibility.**
- **Value**: financial impact (from business cases where they exist) plus strategic weight (capability built, risk retired, option created) — kept as a *separate visible score*, not blended invisibly into the number.
- **Feasibility**: technical difficulty, data/system readiness, change load on the organisation, and dependency risk. For AI initiatives, data readiness and workflow-integration difficulty typically dominate and are typically underestimated — score them explicitly.
Score with rationale per cell; a bare 4/5 is unauditable.

**3. Apply the capacity constraint.** Prioritisation against infinite capacity is a wish list. Establish the real constraints — funding, engineering capacity, change absorption of the affected teams — and draw the cut line where capacity is exhausted, not where enthusiasm runs out.

**4. Sequence above the line.** Order by: hard dependencies first; then learning value (initiatives that de-risk later ones move up); then quick wins that fund or legitimise the programme. Balance the portfolio across horizons — all-quick-wins builds nothing; all-big-bets delivers nothing for a year.

**5. Publish the not-doing list.** Initiatives below the line, each with the reason and the condition that would revive it. This list is what makes the priority list credible, and it prevents zombie projects resurrecting silently.

Before drafting the final deliverable, load `references/deliverable.md` for the output template and quality bar.

## Hand-offs

Consumes **consulting-os-business-cases** (10) and capability gaps from **consulting-os-operating-model-design** (12); respects allocations from **consulting-os-portfolio-review** (11). The sequenced plan is the direct input to **consulting-os-transformation-roadmaps** (14).
