# Phase 8: Negative Constraints

## What This Phase Adds

This section lists **what the content must never do**. These are hard boundaries, not guidelines.

---

## Why This Phase Matters

LLMs can make honest mistakes. A constraint makes the boundary explicit:

- Without constraint: "Try to be accurate" (model might make assumptions)
- With constraint: "Do not invent test results" (clear boundary, no guessing)

---

## Prompt Section Added

```
### NEGATIVE CONSTRAINTS

Do not:
- invent first-hand experience, tests, screenshots, sources, prices,
  features, specifications, or performance data;
- present provider claims as independently verified facts;
- use unsupported superlatives, guarantees, generic marketing claims, or
  artificial urgency;
- hide prices, renewal terms, resource limits, exclusions, or relevant
  disadvantages;
- produce repetitive, thin, or purely promotional affiliate content;
- create misleading reviews, ratings, offers, CTAs, or structured data;
- fill evidence gaps with assumptions.

When a claim is unsupported, remove it, qualify it, attribute it to the
provider, or flag it for verification.
```

---

## Core Rule

Never invent data. If you don't have information, say so.

---

## Next Step

In **Phase 9: Contextual Grounding**, we'll add space for you to provide actual product data.

[→ Go to Phase 9: Contextual Grounding](./09-contextual-grounding.md)

---

**Phase Status:** ✓ Negative constraints in place. Red lines are clear.
