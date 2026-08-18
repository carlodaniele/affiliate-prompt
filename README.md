# Affiliate Content Prompt Template
# Phase 1: Persona and Audience

## What This Phase Adds

The first section of the prompt defines **who the AI is** (your editorial perspective) and **who it's writing for** (reader level, background, assumptions).

This is foundational. Everything that follows—tone, depth, terminology, CTA style—flows from this definition.

---

## Why This Phase Matters

Without a clear persona and audience, the model has no frame of reference. It might:

- Pitch content to the wrong reader level (too technical for beginners, too basic for experts)
- Use jargon without explanation (or over-explain obvious concepts)
- Adopt a tone misaligned with your brand
- Make assumptions about reader knowledge that don't match reality

This phase prevents those failures by making the model's editorial voice and audience assumptions explicit.

---

## Prompt Section Added

```
### PERSONA

You are a senior editorial content strategist and technical writer for an
independent affiliate publisher covering [industry, product category, and
relevant topics].

### AUDIENCE

Write for [general audience].

Assume [technical or subject-matter level]. Explain specialized terms at
first mention and connect important features to practical consequences for
the reader.
```

---

## Key Definitions

### Persona

Your persona is the **editorial identity** the AI should adopt. Examples:

- "You are a senior editorial strategist for an independent WordPress hosting reviewer."
- "You are a technical writer and product comparison expert for a software developer audience."
- "You are a financial advisor and investment analyst for early-career professionals."

The persona should reflect your publisher's expertise and credibility in the industry.

### Audience

The audience definition should specify:

1. **Who they are** (e.g., "small business owners with 5–50 employees")
2. **Their background** (e.g., "non-technical, budget-conscious, time-poor")
3. **What they assume** (e.g., "they understand basic accounting but not payroll software")
4. **What to explain** (e.g., "always explain tax compliance implications; assume they'll use this software themselves, not hire a consultant")

---

## How to Fill This In

### For Your Persona

Ask yourself:

- What industry or product category do we cover?
- What editorial perspective do we bring? (independent, expert, buyer-focused, etc.)
- What is our credibility signal? (years of experience, testing labs, editorial process, audience trust)

### For Your Audience

Ask yourself:

- Who will read this content?
- What is their technical / subject-matter level?
- What terms do they know? What must be explained?
- What are their constraints? (budget, time, risk tolerance, technical skills)
- What will they do after reading? (learn, compare, buy, troubleshoot)

---

## Example Filled-In Phase 1

```
### PERSONA

You are a senior editorial content strategist and technical writer for an
independent affiliate publisher covering WordPress hosting and website-building
platforms.

### AUDIENCE

Write for small business owners and freelancers building their first or second
website.

Assume basic computer literacy but no WordPress or web hosting knowledge.
Explain technical terms like "bandwidth," "SSL certificate," and "uptime" at
first mention. Connect hosting features to practical business consequences
(e.g., "unlimited bandwidth means your site won't slow down if you get a
traffic spike during a promotion").
```

---

## Full Prompt So Far

See the accumulated prompt:

[Phase 1 Prompt](../prompt/phase-01.md)

---

## Reflection Questions

Before moving to Phase 2, ask yourself:

- ✓ Is our persona authentic and defensible?
- ✓ Does it reflect our actual expertise and editorial approach?
- ✓ Is the audience definition specific enough to guide tone and depth?
- ✓ Would a reader recognize this voice as coming from our publisher?

---

## Next Step

In **Phase 2: Funnel Stage**, we'll add logic that adjusts content depth, CTA type, and commercial orientation based on where the reader is in their decision journey (Awareness → Consideration → Decision).

[→ Go to Phase 2: Funnel Stage](./02-funnel-stage.md)

---

**Phase Status:** ✓ Foundational section complete. Persona and audience are set. Ready to add funnel logic.
