# Phase 12: Few-Shot Examples and Output Schema

## What This Phase Adds

This section provides:

1. **Few-shot examples:** Sample input/output pairs so the model learns by example
2. **Output schema:** Explicit structure the model should follow

---

## Why This Phase Matters

Without examples and schema, the model interprets your instructions subjectively. With them, the model knows:

- Exactly what good output looks like
- How evidence should be presented
- What tone to adopt
- How to structure sections
- What level of depth is appropriate

---

## Prompt Section Added

```
## FEW-SHOT EXAMPLES

Use the following examples only to learn structure, tone, evidence handling,
and recommendation style. Do not copy their wording, facts, or conclusions.
The examples are illustrative patterns, not current product documentation.

<EXAMPLE>
  <INPUT>
    [insert representative input]
  </INPUT>

  <OUTPUT>
    [insert approved output showing the desired tone, structure, evidence
    handling, and recommendation style]
  </OUTPUT>
</EXAMPLE>

## OUTPUT SCHEMA

Generate the output in [Markdown / HTML / Gutenberg blocks / JSON] and
follow this structure:

1. TITLE
   - [title requirements]

2. INTRODUCTION
   - [problem, audience, and scope]

3. MAIN CONTENT
   - [required sections or features]
   - [benefits, evidence, limitations, and use cases]

4. PROS AND CONS
   - Include only evidence-supported points.

5. WHO IT IS FOR
   - Identify suitable and unsuitable user profiles.

6. FINAL ASSESSMENT AND CTA
   - Provide a conditional recommendation.
   - Include the affiliate disclosure where required.
   - Use a CTA appropriate to the funnel stage.
   - Include an affiliate link only if supplied in the context or task.

7. SOURCES AND CLAIMS TO VERIFY
   - List important sources.
   - Identify claims requiring verification before publication.
   - Include verification dates when available.

Do not add unrelated sections or fill required fields with unsupported
information.
```

---

## How to Use This

- **Examples teach by demonstration** — Show structure, tone, evidence handling, and recommendation style
- **Schema ensures consistency** — Guarantees every output follows the same structure
- **Customize for your content type** — Adjust headings and sections based on needs

---

## Next Step

In **Phase 13: Complete Template**, we'll assemble everything into one ready-to-use file.

[→ Go to Phase 13: Complete Template](./13-complete-template.md)

---

**Phase Status:** ✓ Examples and schema provided. Model has concrete reference for output quality.
