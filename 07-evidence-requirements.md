# Phase 7: Evidence Requirements

## What This Phase Adds

This section tells the model to **distinguish between types of evidence** and to use the appropriate evidence for different types of claims.

---

## Why This Phase Matters

The biggest credibility killer in affiliate content is presenting unverified vendor claims as independent facts.

---

## Prompt Section Added

```
### EVIDENCE REQUIREMENTS

Base factual claims on appropriate evidence. Distinguish between:

- independently verified information;
- supplier or provider claims;
- first-hand experience;
- test results and measurements;
- editorial opinions;
- interpretations and inferences.

Do not invent features, prices, specifications, performance data, sources,
testing, customer results, or personal experience.

Attribute important provider claims and identify when they have not been
independently confirmed.

Do not generalize from a single test or observation to all users.

For time-sensitive information, identify the source and verification date
when available.

If evidence is missing, outdated, contradictory, or insufficient, flag it
instead of guessing.
```

---

## Key Principles

- Distinguish: verified facts vs. vendor claims vs. opinions vs. tests
- Never invent features, prices, or testing
- Attribute vendor claims: "According to X..."
- Flag unverified information
- Don't generalize from one test
- Always include dates for time-sensitive info

---

## Next Step

In **Phase 8: Negative Constraints**, we'll specify hard boundaries.

[→ Go to Phase 8: Negative Constraints](./08-negative-constraints.md)

---

**Phase Status:** ✓ Evidence standards established. Claims will be grounded in appropriate evidence.
