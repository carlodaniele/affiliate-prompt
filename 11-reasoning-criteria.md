# Phase 11: Reasoning Criteria

## What This Phase Adds

This section is a **self-validation checklist** the model uses before outputting content.

---

## Why This Phase Matters

This is where quality control happens. A reasoning checklist forces the model to:

1. Verify it identified the reader's intent correctly
2. Audit its own evidence
3. Check for trade-offs and limitations
4. Confirm balance and fairness
5. Validate accuracy before publishing
6. Ensure compliance with editorial standards

---

## Prompt Section Added

```
## REASONING CRITERIA

Before writing:

1. Identify the reader's intent, funnel stage, and decision criteria.
2. Select the evidence relevant to the task.
3. Distinguish facts, provider claims, first-hand observations, test
   results, opinions, and inferences.
4. Evaluate benefits, limitations, trade-offs, costs, alternatives, and
   suitability for the target audience.
5. Flag missing, outdated, or contradictory information.
6. Validate the final output for accuracy, relevance, balance, editorial
   integrity, and compliance with the requested format.
```

---

## Key Questions

Before publishing, verify:

- ✓ Reader intent identified correctly?
- ✓ Evidence selected and sourced?
- ✓ Facts vs. claims vs. opinions distinguished?
- ✓ Trade-offs and limitations evaluated?
- ✓ Information gaps flagged?
- ✓ Output accurate, relevant, balanced, and compliant?

---

## Next Step

In **Phase 12: Few-Shot Examples and Output Schema**, we'll show examples of good output.

[→ Go to Phase 12: Few-Shot Examples and Output Schema](./12-few-shot-examples-and-output-schema.md)

---

**Phase Status:** ✓ Reasoning criteria established. Model has a self-validation checklist.
