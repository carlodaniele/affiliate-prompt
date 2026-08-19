## Gutenberg block structure (optional)

Add the following section if you want your content ready for Gutenberg 

```
## GUTENBERG BLOCK STRUCTURE

Generate the article using valid native WordPress Gutenberg block markup.

Use the following Gutenberg blocks and structural rules throughout the article.

### Supported blocks

Use these native Gutenberg blocks when appropriate:

- **Heading:** Use `wp:heading` for H2 and H3 headings.
- **Paragraph:** Use `wp:paragraph` for standard body text.
- **Image:** Use `wp:image` for relevant editorial images, screenshots, diagrams, or other visual content.
- **Blockquote:** Use `wp:quote` for relevant quotations, expert statements, or short passages that deserve visual emphasis.
- **Columns:** Use `wp:columns` and `wp:column` when a two-column layout improves the presentation of related content.
- **Buttons:** Use `wp:buttons` and `wp:button` for prominent calls to action.
- **Group:** Use `wp:group` to visually group related content, especially CTA sections.

---

### Heading rules

Use H2 headings for main sections and H3 headings for subsections.

Example:

<!-- wp:heading -->
<h2 class="wp-block-heading">Heading 2</h2>
<!-- /wp:heading -->

<!-- wp:heading {"level":3} -->
<h3 class="wp-block-heading">Heading 3</h3>
<!-- /wp:heading -->

Do not use H1 inside the article body because the article title is handled separately by WordPress.

---

### Paragraph rules

Use a separate `wp:paragraph` block for each logical paragraph.

Example:

<!-- wp:paragraph -->
<p>Paragraph</p>
<!-- /wp:paragraph -->

Avoid unnecessarily long paragraphs. Prefer short to medium-length paragraphs that improve readability and scanning.

---

### Image rules

Use the `wp:image` block for images that provide genuine editorial value.

Images may include:
- product or interface screenshots;
- diagrams;
- explanatory visuals;
- relevant editorial images;
- visual examples that help explain a technical concept.

Do not add decorative images merely to increase visual density.

When image information is provided, preserve the supplied image ID, URL, dimensions, and attributes. Do not invent image metadata.

Example:

<!-- wp:image {"id":17093,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large">
  <img src="http://wordpress.kinsta.cloud/wp-content/uploads/2026/07/20260704_135055-1024x768-1.jpg" alt="" class="wp-image-17093"/>
</figure>
<!-- /wp:image -->

If no valid image asset is provided, do not invent one.

---

### Blockquote rules

Use the `wp:quote` block for quotations that add meaningful evidence, expert perspective, or editorial emphasis.

Do not use blockquotes merely for visual styling.

Example:

<!-- wp:quote -->
<blockquote class="wp-block-quote">
  <!-- wp:paragraph -->
  <p>Example quote</p>
  <!-- /wp:paragraph -->
</blockquote>
<!-- /wp:quote -->

Do not fabricate quotations or attribute statements without evidence.

---

### Columns rules

Use `wp:columns` when presenting two related pieces of information side by side, such as an image and explanatory content.

Example:

<!-- wp:columns -->
<div class="wp-block-columns">

  <!-- wp:column -->
  <div class="wp-block-column">
    <!-- wp:image -->
    <figure class="wp-block-image"><img alt=""/></figure>
    <!-- /wp:image -->
  </div>
  <!-- /wp:column -->

  <!-- wp:column -->
  <div class="wp-block-column">

    <!-- wp:heading {"level":3} -->
    <h3 class="wp-block-heading">Heading 3</h3>
    <!-- /wp:heading -->

    <!-- wp:paragraph -->
    <p>Paragraph</p>
    <!-- /wp:paragraph -->

    <!-- wp:buttons -->
    <div class="wp-block-buttons">
      <!-- wp:button -->
      <div class="wp-block-button">
        <a class="wp-block-button__link wp-element-button">Click here</a>
      </div>
      <!-- /wp:button -->
    </div>
    <!-- /wp:buttons -->

  </div>
  <!-- /wp:column -->

</div>
<!-- /wp:columns -->

Use columns only when they improve comprehension or visual hierarchy.

---

### CTA rules (IMPORTANT)

Calls to action must be visually prominent and clearly distinguishable from regular content.

For affiliate content, use CTA blocks at key decision points rather than only at the end.

#### CTA structure (mandatory pattern)

Each CTA must be wrapped in a `wp:group` containing:

1. A heading (value proposition or action)
2. A short paragraph (context or benefit)
3. A `wp:buttons` block with a `wp:button`

Example:

<!-- wp:group -->
<div class="wp-block-group">

  <!-- wp:heading {"level":3} -->
  <h3 class="wp-block-heading">Ready to explore Kinsta?</h3>
  <!-- /wp:heading -->

  <!-- wp:paragraph -->
  <p>Review the current plans and see whether Kinsta's managed WordPress hosting fits your requirements.</p>
  <!-- /wp:paragraph -->

  <!-- wp:buttons -->
  <div class="wp-block-buttons">
    <!-- wp:button -->
    <div class="wp-block-button">
      <a class="wp-block-button__link wp-element-button">View Kinsta Plans</a>
    </div>
    <!-- /wp:button -->
  </div>
  <!-- /wp:buttons -->

</div>
<!-- /wp:group -->

#### CTA rules

- Must be visually prominent
- Must communicate a clear next step
- Must be appropriate for MOFU intent
- Must avoid hype or urgency manipulation
- Must avoid unsupported claims
- Must not imply universal suitability
- Must use affiliate link only if provided
- Do not overuse CTAs (2–3 per article max depending on length)

---

### Gutenberg validity rules

- Use native WordPress Gutenberg block syntax only
- Every opening block must have a closing block
- Maintain correct nesting
- Do not mix Markdown and Gutenberg inside blocks
- Do not invent custom blocks
- Do not invent attributes unless provided
- Keep HTML valid inside blocks
- Do not output explanations outside the article unless explicitly requested

---
```