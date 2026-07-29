---
name: consulting-os-fact-base
description: Build the shared, sourced fact base for an engagement — the numbers and facts everyone argues from. Use whenever the user needs to gather, verify, or organise evidence for a client engagement; mentions a fact pack, data book, baseline, "what do we actually know", source-of-truth numbers, or is about to make claims in a deliverable that need substantiation. Skill 02 of the consulting suite, following problem framing.
version: 1.0.0
title: "Fact Base"
status: active
---

# The Fact Base

Engagements fail politically when the team and the client argue from different numbers. The fact base is a single, sourced, versioned set of facts that the whole engagement stands on. Every downstream claim traces back to it.

## Method

**1. Derive the fact list from the issue tree.** Each priority leaf implies specific facts needed. Do not gather data speculatively — every fact earns its place by serving a branch.

**2. Classify each fact by grade:**
- **A** — audited/primary (client financials, signed contracts, system extracts).
- **B** — credible secondary (regulator filings, reputable industry data, named analyst reports).
- **C** — estimate or triangulation (state the method).
- **D** — assertion (someone said so). D-grade facts may not support recommendations; they go to the assumption log.

**3. Record facts in a ledger, one row per fact:** the fact itself, value, unit, period, source (specific enough to re-find), grade, date retrieved, and which issue-tree branch it serves.

**4. Triangulate anything load-bearing.** Any fact that a recommendation rests on needs two independent sources, or one A-grade source. Where sources disagree, record both and the resolution logic — never silently pick one.

**5. Baseline the client's own numbers first.** The client's revenue, cost, headcount, and volume figures anchor everything; external data is calibrated against them, not the reverse.

## Workflow

1. Take the issue tree (or ask for the questions being answered) and list the facts required per branch.
2. Gather: client data first, then public/secondary. Use web search where appropriate; cite specifically.
3. Grade, triangulate, and log. Flag every gap explicitly rather than papering over it.
4. Publish the fact base as a table plus a one-page "headline facts" summary the client sponsor can sign off.

Before drafting the final deliverable, load `references/deliverable.md` for the output template and quality bar.

## Hand-offs

Feeds every analytical skill (04–11). D-grade facts and unresolved conflicts go to **consulting-os-assumption-audits** (03). Headline facts become the "Situation" evidence in **consulting-os-executive-narrative** (19).
