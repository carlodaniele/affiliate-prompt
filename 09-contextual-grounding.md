# Phase 9: Contextual Grounding

## What This Phase Adds

This section creates a space for **you to provide factual data** about the product, market, publisher, and sources.

---

## Why This Phase Matters

The most common failure mode is: "The model made up information because I didn't give it accurate data to start with."

This section forces you to gather and structure:

- What you actually know about the product
- What sources you've verified
- What testing you've done
- What you still need to research

---

## Prompt Section Added

```
## CONTEXTUAL GROUNDING

Use the following information as the factual and editorial context:

- Publisher profile: [expertise and editorial positioning].
- Provider, product, or service: [name].
- Service or product category: [category].
- Market and language: [market and language].
- Available sources: [official documentation, pricing pages, terms,
  independent tests, and other sources].
- Verified product information: [features, plans, pricing, renewal terms,
  limits, conditions].
- First-hand evidence: [tests, screenshots, measurements, observations, or
  "not available"].
- Relevant alternatives or comparison material: [insert only if required].
- Known limitations or unresolved issues: [details or "none identified"].

Use the supplied sources as the factual basis for product-specific claims.
Flag missing, outdated, contradictory, or unsupported information instead of
guessing.
```

---

## What Each Field Means

- **Publisher profile:** Your expertise and credibility
- **Provider/Product:** What you're reviewing
- **Category:** Market/category context
- **Market/Language:** Geographic and language scope
- **Available sources:** Links to official docs, pricing, tests
- **Verified information:** What you've confirmed (features, pricing, limits)
- **First-hand evidence:** Your tests or observations
- **Alternatives:** Competing products
- **Known limitations:** Gaps or tradeoffs

---

## Next Step

In **Phase 10: Task Instructions**, we'll specify exactly what to create.

[→ Go to Phase 10: Task Instructions](./10-task-instructions.md)

---

**Phase Status:** ✓ Contextual grounding prepared. Model has factual foundation.
