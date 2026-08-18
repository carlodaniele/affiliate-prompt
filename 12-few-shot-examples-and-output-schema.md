## Affiliate content prompt tempate: Few-shot examples and output schema

```
## SYSTEM INSTRUCTIONS

## CONTEXTUAL GROUNDING

## TASK INSTRUCTIONS

## REASONING CRITERIA

---

## FEW-SHOT EXAMPLES

Use the following examples only to learn structure, tone, evidence handling, and recommendation style. Do not copy their wording, facts, or conclusions. The examples are illustrative patterns, not current product documentation.

<EXAMPLE>
  <INPUT>
    Create: Product review
    Product: [Example WordPress Hosting]
    Funnel stage: BOFU
    Audience: Small web agencies
    Verified information: Pricing, features, setup time, support response
    Comparison products: [Competitor A, Competitor B]
  </INPUT>

  <OUTPUT>
    # [Product Name]: Full Review, Pricing, and Who It's Best For

    ## Introduction

    [Product] is well-suited for [specific audience]. This review covers pricing, features, setup process, and who it's best for.

    This review is based on first-hand testing (August 2026) and official documentation.
    **I earn a commission if you sign up through this link.**

    ## Pricing

    [Clear pricing table with all plans and details]

    ## Features (Verified)

    [Tested and verified features listed]

    ## Performance

    [First-hand testing results with specific measurements and dates]

    ## Pros and Cons

    **Pros:**
    - [Evidence-based pro]
    - [Evidence-based pro]

    **Cons:**
    - [Verified limitation]
    - [Verified limitation]

    ## Who It's Best For

    **Excellent fit:**
    - [Specific audience profile]

    **Consider alternatives:**
    - [Profile better served by competitor]

    ## Alternatives

    [Non-affiliate and affiliate alternatives with brief comparison]

    ## Final Assessment

    [Conditional recommendation based on evidence]

    [→ CTA that matches funnel stage]

    ## Sources

    [List of sources used]

  </OUTPUT>

</EXAMPLE>

---

## OUTPUT SCHEMA

Generate the output in [Markdown / HTML / Gutenberg blocks / JSON] and
follow this structure:

1. TITLE
   - Clear, descriptive, includes main keyword
   - Format: "[Product]: [Main Question/Aspect]"

2. INTRODUCTION
   - Problem or use case addressed
   - Who the content is for
   - Scope and what readers will learn
   - Affiliate disclosure (if applicable)

3. MAIN CONTENT
   - Pricing and plans (if applicable)
   - Features and functionality
   - Performance or results (if tested)
   - Setup and onboarding
   - Limitations or gotchas

4. PROS AND CONS
   - Evidence-based points only
   - Balanced (roughly equal pros and cons)
   - Specific, not generic

5. WHO IT IS FOR
   - Ideal use cases and profiles
   - Profiles where alternatives are better
   - Clear decision criteria

6. FINAL ASSESSMENT AND CTA
   - Conditional recommendation (not universal)
   - What to do next
   - CTA appropriate to funnel stage
   - Affiliate link (if provided in context)

7. SOURCES AND CLAIMS TO VERIFY
   - Important sources used
   - Claims requiring verification
   - Verification dates

Do not add unrelated sections or fill required fields with unsupported information.

---

## HOW TO USE THIS TEMPLATE

1. **Copy this entire template**
2. **Fill in all bracketed [sections] with your specific information**
3. **Add your CONTEXTUAL GROUNDING with actual product data**
4. **Add your TASK INSTRUCTIONS for this specific assignment**
5. **Paste into Claude, ChatGPT, or your preferred LLM**
6. **Review output and refine as needed**

For detailed guidance on each section, refer to the phase-by-phase guide in the main README.

---

**Template Version:** 1.0 | **Last Updated:** August 2026

```