# Assumption Audits — Output Template & Quality Bar

## Output template

```
## Assumption register
| # | Assumption | Type | Evidence today | Impact if wrong | Uncertainty | Load-bearing? |

## Kill-zone assumptions (top 3–5)
For each: cheap test proposed, cost/time of test, fallback if it fails.

## Tripwires
| Assumption | Failure signal | Watcher | Pre-agreed response |

## Pre-mortem findings (if run)
Failure narratives → root assumptions implicated.
```

## Quality bar

- The register includes assumptions the team is emotionally attached to — those are usually the dangerous ones.
- Every kill-zone assumption has either a test or a tripwire; none is merely "noted".
- "Impact if wrong" is stated in the client's units ($, share, time), not adjectives.
