# Phase 3: Editorial Principles

## What This Phase Adds

This section establishes the **editorial foundation** that prevents affiliate content from becoming thin, promotional, or unreliable.

It tells the model: "Your job is to help readers make informed decisions. Affiliate revenue is secondary."

---

## Why This Phase Matters

Affiliate content is inherently risky. The financial incentive can tempt even honest publishers to:

- Recommend products based on commission value, not reader fit
- Omit or downplay limitations to make products sound better
- Use vague language to avoid committing to a stance
- Prioritize persuasion over usefulness

This phase protects against those shortcuts by explicitly aligning the model with editorial integrity.

---

## Prompt Section Added

```
### EDITORIAL PRINCIPLES

Create content that readers can trust and use to make informed decisions.

Prioritize:
- original value beyond supplier-provided information;
- first-hand experience and original observations when available;
- practical advice connected to real user needs;
- balanced analysis of benefits, limitations, trade-offs, and alternatives;
- usefulness independent of affiliate clicks or purchases.

Do not describe any product or service as universally best. Explain who it
is suitable for, who should consider alternatives, and under which
conditions the recommendation applies.
```

---

## What This Section Means

### Original Value

Don't just rewording the vendor's marketing materials. Add:

- How does this product fit into a larger ecosystem?
- What alternatives exist, and when would someone choose them?
- What problems does this solution actually solve vs. marketing claims?
- What does first-hand use reveal that marketing pages don't?

### First-Hand Experience

When you have tested a product:

- Share specific observations (speed, user interface, customer service response time)
- Report both strengths and friction points
- Use data or screenshots if available
- Flag claims you couldn't verify personally

### Practical Advice

Connect features to reader needs:

- Bad: "HubSpot has native AI features"
- Good: "HubSpot's native AI features let sales teams write follow-up emails faster, saving ~10 minutes per rep per day on our team"

### Balanced Analysis

Don't hide tradeoffs. Examples:

- "Tool A is cheaper but requires manual data entry"
- "Tool B costs more but integrates with Salesforce, reducing setup time"
- "Service C is easiest to start with but has limitations if you scale beyond 100 customers"

### Usefulness Independent of Affiliate Revenue

The reader should find the content valuable even if:

- They don't click your affiliate link
- They choose a competing product
- They decide not to buy at all

Content that fails without the commission is advertising, not journalism.

### No Universal "Best"

Every product is best for someone and wrong for someone else.

Instead of:

> "HubSpot is the best CRM for small teams."

Write:

> "HubSpot is well-suited for marketing-led teams that want native email, lead scoring, and forms. It's less ideal if you need Salesforce integration or heavy customization. If you need a cheaper entry point, consider Zoho."

This builds reader trust. It says: "I'm not selling you on HubSpot; I'm helping you decide if it fits your situation."

---

## How to Fill This In

### For Your Content

Ask:

- ✓ Can I add original insight beyond what the vendor says?
- ✓ Have I tested this product? Can I share specific observations?
- ✓ What are the real trade-offs? Who should consider alternatives?
- ✓ Would this content help a reader even if they don't buy?
- ✓ Am I describing this product conditionally or as universally best?

### Red Flags

Watch for:

- "Best" without conditions → Always specify "best for whom?"
- Vendor claims without verification → Flag them or verify independently
- Missing downsides → Every product has limitations
- Generic benefits → Replace with specific, observable consequences
- Aggressive CTAs before evidence → Build trust first, then CTA

---

## Example: Editorial Principles in Practice

**Task:** Review WordPress hosting provider for BOFU affiliate content

**Without editorial principles:**
> "Kinsta is the best WordPress hosting provider. It offers unlimited bandwidth, expert support, and 99.9% uptime. Sign up today!"

**With editorial principles:**
> "Kinsta is well-suited for agencies, publishers, and e-commerce sites that need high performance and white-label support. Our testing showed median page load times of 400ms, which is faster than the industry average for managed WordPress hosts. However, Kinsta's pricing ($300+/month) is higher than competitors like SiteGround. If you need a cheaper entry point, consider Bluehost or Hostinger. Kinsta is best if performance and support matter more than cost."

Notice the second version:

- Reports specific test results (400ms)
- Acknowledges trade-offs (higher cost)
- Mentions alternatives
- Explains who it's best for (not "everyone")
- Builds trust → makes the CTA more effective

---

## Full Prompt So Far

See the accumulated prompt:

[Phase 1–3 Prompt](../prompt/phase-03.md)

---

## Reflection Questions

Before moving to Phase 4, ask yourself:

- ✓ Do we have the editorial confidence to say "this product isn't suitable for X"?
- ✓ Are we comfortable adding useful information that might not drive clicks?
- ✓ Do our review processes identify first-hand testing and limitations?
- ✓ Would we trust this content if we were the reader?

---

## Next Step

In **Phase 4: Affiliate Marketing Principles**, we'll add rules that keep affiliate revenue from corrupting editorial judgment.

[→ Go to Phase 4: Affiliate Marketing Principles](./04-affiliate-marketing-principles.md)

---

**Phase Status:** ✓ Editorial principles established. Trustworthiness is now the foundation. Ready for affiliate-specific rules.
