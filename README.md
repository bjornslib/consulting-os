# Consulting OS

Consulting OS is a 21-skill operating system for running a strategy
consulting engagement end to end inside Claude Code: framing the problem,
building a shared fact base, analysing the market and the competition,
deciding what to do, designing how to deliver it, protecting the plan
against risk, and carrying the result to a decision-maker. A meta-skill
(`consulting-os`) sequences the other 20 for the engagement at hand and
converts finished work into reusable IP.

The skills are a kit, not a syllabus. Use the meta-skill to pick and
sequence the right subset for a given engagement type (growth strategy,
pricing, transformation, portfolio review, rapid diagnostic), or invoke any
individual skill directly when you already know what you need.

---

## The 20 methods

**Frame**
1. `consulting-os-problem-framing` — Frame a client problem precisely and decompose it into a MECE issue tree before any analysis begins.
2. `consulting-os-fact-base` — Build the shared, sourced fact base for an engagement — the numbers and facts everyone argues from.
3. `consulting-os-assumption-audits` — Surface, stress-test, and monitor the assumptions underneath a strategy, model, plan, or recommendation.

**Analyse**
4. `consulting-os-market-sizing` — Size a market rigorously — TAM/SAM/SOM, top-down and bottom-up triangulation, growth outlook.
5. `consulting-os-competitive-intelligence` — Build a structured picture of competitors — who they are, how they win, where they are vulnerable, and what they will likely do next.
6. `consulting-os-customer-segmentation` — Segment a customer base or market into groups that behave differently and can be served and reached differently.
7. `consulting-os-profit-pool-analysis` — Map where profit actually sits across a value chain, industry, or customer base — and where it is shifting.

**Decide**
8. `consulting-os-strategic-options` — Generate genuinely distinct strategic options and evaluate them against explicit criteria to reach a recommendation.
9. `consulting-os-pricing-strategy` — Design or review pricing — architecture, level, and metric — grounded in value, willingness to pay, and competitive position.
10. `consulting-os-business-cases` — Build a decision-grade business case or financial model — drivers, scenarios, NPV/payback, and the honest risks.
11. `consulting-os-portfolio-review` — Review a portfolio — business units, products, initiatives, or clients — to decide where to invest, hold, fix, or exit.

**Design**
12. `consulting-os-operating-model-design` — Design or redesign how an organisation delivers its strategy — structure, processes, governance, capabilities, technology, and ways of working.
13. `consulting-os-initiative-prioritisation` — Prioritise a set of initiatives, projects, or use cases against value, feasibility, and capacity, producing a sequenced, funded list and an explicit not-doing list.
14. `consulting-os-transformation-roadmaps` — Turn prioritised initiatives into an executable transformation roadmap — waves, milestones, dependencies, owners, funding gates, and change management.

**Protect**
15. `consulting-os-risk-mitigation` — Identify, quantify, and mitigate the risks to a strategy, transformation, or major decision — with owners, triggers, and pre-agreed responses.
16. `consulting-os-war-gaming` — Run a competitive war game — simulate how competitors, regulators, and other players will respond to a strategic move over multiple rounds, and harden the strategy against those responses.
17. `consulting-os-kpi-architecture` — Design the measurement system for a strategy or transformation — a driver-linked KPI tree, leading and lagging indicators, targets, owners, and dashboards.

**Carry**
18. `consulting-os-stakeholder-alignment` — Map the stakeholders around a decision or change, understand their interests and influence, and run a deliberate alignment campaign.
19. `consulting-os-executive-narrative` — Turn analysis into a persuasive executive narrative and deck — pyramid-principle storyline, action titles, evidence-backed pages.
20. `consulting-os-board-memos` — Write decision-grade board memos and papers — a clear ask, the case for and against, risks, and a specific decision to record.

**Meta**
21. `consulting-os` — Orchestrate the full 21-skill suite: select and sequence the right skills for an engagement, run engagement hygiene (single-sourced artefacts, the assumption-audit gate, continuous stakeholder alignment), and harvest completed engagements into reusable frameworks, benchmarks, prompts, and lessons.

---

## Install

The plugin lives in its own repository, `bjornslib/consulting-os`, with a
one-plugin marketplace. Installation takes two commands in a Claude Code
session:

```
/plugin marketplace add bjornslib/consulting-os
/plugin install consulting-os@consulting-os
```

Restart the session, or enable the plugin from `/plugin`. After that, all 21
skills are available in every project via the `Skill` tool.

## Usage

Start any engagement with the meta-skill to get a sequencing recommendation:

```
Skill("consulting-os")
```

Or invoke any individual method directly once you know what you need, e.g.:

```
Skill("consulting-os-market-sizing")
Skill("consulting-os-executive-narrative")
```

Each skill's `SKILL.md` carries its trigger conditions (the phrases and
situations that should lead you to reach for it) and a `references/deliverable.md`
describing the expected output artefact and quality bar.

## Plugin structure

```
consulting-os/
├── .claude-plugin/
│   ├── plugin.json           # manifest: name "consulting-os", version, keywords
│   └── marketplace.json      # one-plugin marketplace: name "consulting-os", plugins: [{source: "."}]
├── skills/
│   ├── consulting-os/                          # meta-skill (SKILL.md only)
│   ├── consulting-os-problem-framing/          # SKILL.md + references/deliverable.md
│   ├── consulting-os-fact-base/
│   ├── consulting-os-assumption-audits/
│   ├── consulting-os-market-sizing/
│   ├── consulting-os-competitive-intelligence/
│   ├── consulting-os-customer-segmentation/
│   ├── consulting-os-profit-pool-analysis/
│   ├── consulting-os-strategic-options/
│   ├── consulting-os-pricing-strategy/
│   ├── consulting-os-business-cases/
│   ├── consulting-os-portfolio-review/
│   ├── consulting-os-operating-model-design/
│   ├── consulting-os-initiative-prioritisation/
│   ├── consulting-os-transformation-roadmaps/
│   ├── consulting-os-risk-mitigation/
│   ├── consulting-os-war-gaming/
│   ├── consulting-os-kpi-architecture/
│   ├── consulting-os-stakeholder-alignment/
│   ├── consulting-os-executive-narrative/
│   └── consulting-os-board-memos/
├── LICENSE
└── README.md                  # this file
```

The plugin ships no agents, no hooks, no MCP servers, no output styles, and
no slash commands — every method is invoked as a skill. This is deliberate:
the plugin must work in any session without touching that session's
permission or hook surface. Claude Code auto-discovers `skills/` from its
default directory location, so the manifest does not need to declare it.

## Origin

These 21 skills were developed and used inside `bjornslib/cobuilder-harness`
and are extracted here verbatim as a standalone, installable plugin.
