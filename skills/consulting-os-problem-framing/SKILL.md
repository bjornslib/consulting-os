---
name: consulting-os-problem-framing
description: Frame a client problem precisely and decompose it into a MECE issue tree before any analysis begins. Use whenever an engagement, workshop, proposal, or analysis is starting; whenever the user mentions a vague client problem, a new brief, "where do we start", scoping, hypotheses, SCQA, issue trees, or asks to structure a messy situation. This is skill 01 of the consulting suite — if no other skill has run yet in an engagement, start here.
version: 1.0.0
title: "Problem Framing"
status: active
---

# Problem Framing & Issue Trees

The most expensive mistake in consulting is solving the wrong problem well. This skill converts a vague client situation into a precise, decision-oriented problem statement and a MECE issue tree that scopes all downstream work.

## Method

**1. Write the problem statement using SCQA.**
- **Situation** — uncontested facts about where the client is.
- **Complication** — what changed or threatens; why the status quo is untenable.
- **Question** — the single governing question, phrased as a decision ("Should X…", "How should Y…"), not a topic.
- **Answer (hypothesis)** — the current best guess, stated so it can be proven wrong.

A good governing question passes three tests: it is answerable within the engagement's time and data constraints; the answer changes a real decision; the client's sponsor would recognise it as *their* question.

**2. Decompose into an issue tree.**
- Break the governing question into 3–5 first-level issues that are **MECE** (mutually exclusive, collectively exhaustive).
- Choose a decomposition logic and state it: algebraic (profit = revenue − cost), process (acquire → convert → retain), stakeholder, hypothesis-driven, or options-based.
- Go two to three levels deep. Stop when a branch becomes a concrete, answerable analytical question.
- For hypothesis-driven trees, phrase each branch as a testable assertion, not a topic ("SME churn is driven by onboarding failure" not "churn").

**3. Prioritise branches.**
Kill or park branches that are unlikely to change the answer. Mark each remaining leaf with: the analysis needed, the data source, and the owner. This becomes the workplan.

## Workflow

1. Interview the user for the raw client context. If the brief is thin, ask for: who the decision-maker is, what decision they face, the deadline, and what "good" looks like to them.
2. Draft the SCQA and the governing question. Confirm with the user before building the tree — a wrong question makes the tree worthless.
3. Build the tree, state the decomposition logic, and check MECE explicitly (overlaps? gaps?).
4. Prioritise leaves and produce the day-one workplan.

Before drafting the final deliverable, load `references/deliverable.md` for the output template and quality bar.

## Hand-offs

Feeds **consulting-os-fact-base** (02): each priority leaf defines what facts to gather. If assumptions were made to frame the problem, log them for **consulting-os-assumption-audits** (03).
