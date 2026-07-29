---
name: consulting-os-war-gaming
description: Run a competitive war game — simulate how competitors, regulators, and other players will respond to a strategic move over multiple rounds, and harden the strategy against those responses. Use whenever the user mentions war-gaming, competitive response, "what will competitors do", scenario simulation of a move (launch, price change, entry, M&A), red teaming a strategy against the market, or stress-testing a plan against reactions. Skill 16 of the consulting suite.
version: 1.0.0
title: "War Gaming"
status: active
---

# Competitive War-Gaming

Strategies are usually evaluated against a frozen world; markets are not frozen. A war game plays the client's move forward several rounds through the eyes of the other players — and the output is not "who won" but a hardened strategy and a set of pre-agreed responses.

## Method

**1. Define the game.** The client move under test (specific, not "our strategy generally"), the time horizon (usually 2–3 simulated years across 3 rounds), the market battleground, and what winning means for each player.

**2. Build player briefs.** For each significant player (from competitive-intelligence profiles): objectives, economics and constraints, decision style and speed, and available moves. The brief must be strong enough that someone playing that competitor makes decisions *the competitor would make*, not decisions that flatter the client. Include non-obvious players where relevant: regulators, key channel partners, a potential entrant, major customers.

**3. Play rounds.** Each round: the client team commits its move → each player team responds in character, with their economics constraining what they can afford → the control team adjudicates market outcomes (share, price levels, margin shifts) using explicit, stated logic — adjudication by vibes discredits the whole exercise. Publish the round's state, then play the next.

**4. Watch for the classic findings.** Price moves get matched faster than assumed; the strongest response often comes from the player with the most to lose, not the largest; the client's move often creates space for a *third* player; regulators move slower but harder than expected. Test asymmetric responses — a competitor may respond in a different arena than the one attacked.

**5. Harvest.** Which client moves survived contact; which triggered ruinous responses; which competitor responses were most damaging and what early signals would precede them; what pre-emptive or contingent moves the client should prepare. Convert damaging responses into trigger→response pairs.

Run this solo (Claude playing all sides with the discipline of the briefs) for a fast desk war game, or use it to design and adjudicate a live workshop with client teams playing the parts.

Before drafting the final deliverable, load `references/deliverable.md` for the output template and quality bar.

## Hand-offs

Player briefs come from **consulting-os-competitive-intelligence** (05). Tests the leader from **consulting-os-strategic-options** (08) and exposed moves from **consulting-os-pricing-strategy** (09). Trigger→response pairs feed **consulting-os-risk-mitigation** (15); signal-watching joins **consulting-os-kpi-architecture** (17).
