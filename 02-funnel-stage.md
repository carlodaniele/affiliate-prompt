# Phase 2: Funnel Stage

## What This Phase Adds

The second section tells the model to adapt content depth, CTA type, and commercial orientation to match the reader's **decision stage**: Awareness (TOFU), Consideration (MOFU), or Decision (BOFU).

This is critical for affiliate content. A reader in the awareness phase needs education and problem explanation, not a hard sell. A reader in the decision phase needs to compare options and understand pricing before buying.

---

## Why This Phase Matters

Affiliate content fails when the pitch is wrong for the reader's stage. Examples:

- **Wrong:** Sending a reader deep into pricing and feature comparisons when they haven't yet decided whether they have the problem
- **Wrong:** Writing a soft educational intro when the reader is ready to buy and just needs to know which option suits them best
- **Wrong:** Using vague CTAs ("learn more") when the reader is ready for a transactional link

This phase prevents misalignment by making funnel stage explicit and adjusting content strategy accordingly.

---

## Prompt Section Added

```
### FUNNEL

Always adapt content depth, CTA type, and commercial orientation to the
funnel stage specified in the task.

TOFU:
Prioritize education, awareness, and problem explanation. Avoid premature
recommendations and aggressive CTAs.

MOFU:
Help readers compare approaches, technologies, products, services, costs,
trade-offs, and use cases. Use CTAs appropriate to their decision readiness.

BOFU:
Reduce uncertainty before the purchase decision. Analyze products,
services, or plans using verifiable information, including benefits,
limitations, costs, conditions, and suitability for the reader's profile.
Use transparent commercial CTAs.

Maintain the same standards of accuracy, balance, and transparency at every
funnel stage.
```

---

## Understanding the Funnel Stages

### TOFU (Top of Funnel): Awareness

**Reader mindset:** "Do I have this problem? What options exist?"

**Content approach:**
- Explain the problem and why it matters
- Introduce the landscape of solutions (without heavy recommendations)
- Answer "what is it?" and "why might I care?"
- Educate on terminology, best practices, and decision criteria

**CTA style:**
- Soft, educational CTAs ("download a checklist," "read the guide," "learn more about how to evaluate options")
- No affiliate links unless absolutely natural
- Focus on helping them clarify whether they have the problem

**Examples:**
- "What is email marketing automation, and why small teams use it"
- "How to decide if your business needs a chatbot"
- "Common web hosting problems and what causes them"

### MOFU (Middle of Funnel): Consideration

**Reader mindset:** "I have this problem. What are the main approaches? How do they compare?"

**Content approach:**
- Compare approaches, technologies, products, or services
- Explain trade-offs, costs, and use cases
- Help readers narrow their options based on criteria
- Provide balanced analysis of pros and cons

**CTA style:**
- Decision-support CTAs ("compare these tools," "see the pricing comparison," "request a demo")
- Affiliate links are natural here (comparing options means steering toward specific products)
- Focus on helping them move toward a choice

**Examples:**
- "Email marketing automation tools for small teams: Comparison of features, pricing, and use cases"
- "WordPress vs. Wix: Which website builder is right for you?"
- "SaaS vs. self-hosted: When to choose each architecture"

### BOFU (Bottom of Funnel): Decision

**Reader mindset:** "I've decided what I need. Does this specific product fit my use case? What does it cost? Any hidden gotchas?"

**Content approach:**
- Deep dive into specific products or services
- Analyze pricing, contracts, conditions, limitations
- Address common decision-making objections
- Reduce final-stage uncertainty

**CTA style:**
- Transactional CTAs ("get started," "sign up," "buy now")
- Affiliate links are explicit and well-integrated
- Focus on closing the decision with confidence

**Examples:**
- "Kinsta WordPress Hosting: Full review, pricing breakdown, and who it's best for"
- "HubSpot vs. Salesforce: Detailed comparison for SMB sales teams"
- "ClickUp Pro plan: Full feature walkthrough and pricing analysis"

---

## How to Fill This In

### Choose Your Funnel Stage

For your content task, decide:

- **TOFU:** The reader is learning about a problem or landscape for the first time
- **MOFU:** The reader is comparing specific approaches or products
- **BOFU:** The reader is evaluating a specific product or service before purchase

### Adjust Your Approach

Once you've chosen, your task instructions and CTA should reflect that stage.

For TOFU, don't demand affiliate clicks. Prioritize education.
For MOFU, comparisons and links are natural.
For BOFU, transactional CTAs and affiliate links are expected.

---

## Example Funnel Stages in Practice

**Same product, three funnel stages:**

1. **TOFU:** "What is WordPress hosting, and why does it matter?" (educational, light touch)
2. **MOFU:** "WordPress hosting providers compared: Managed vs. unmanaged" (comparison, balanced options)
3. **BOFU:** "Kinsta WordPress hosting: Full review, pricing, and who it's for" (product deep-dive, affiliate link)

The same publisher might create all three pieces targeting the same reader over time as they move through the funnel.

---

## Full Prompt So Far

See the accumulated prompt with Persona + Funnel:

[Phase 1–2 Prompt](../prompt/phase-02.md)

---

## Reflection Questions

Before moving to Phase 3, ask yourself:

- ✓ Do we understand the three funnel stages?
- ✓ Can we identify which stage our content targets?
- ✓ Are our CTAs aligned with reader decision-readiness?
- ✓ Would we feel confident adjusting content depth based on this funnel model?

---

## Next Step

In **Phase 3: Editorial Principles**, we'll add rules that ensure affiliate content prioritizes reader value and editorial integrity over commercialization pressure.

[→ Go to Phase 3: Editorial Principles](./03-editorial-principles.md)

---

**Phase Status:** ✓ Funnel stage logic added. Content depth is now aligned with reader intent. Ready for editorial principles.
