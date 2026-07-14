# ♿ Workshop 19: Accessibility & Semantic Refactor

A document refactoring project focused on repairing semantic hierarchy inconsistencies, landmark structures, and assistive technology outlines.

## 🛠️ Refactoring Transformations (Before vs. After)

This workshop involved fixing a legacy layout that violated several accessibility rules. Here is what was corrected:

1. **Heading Outline Consolidation (`<h1>` to `<h2>` / `<h3>`):**
   * *Before:* The document layout structure incorrectly used multiple `<h1>` elements for article subtitles, confusing screen reader navigation algorithms.
   * *After:* Fixed the nesting structure to utilize a single dominant `<h1>` element, organizing subtitles down sequentially into standard structural `<h2>` context zones and `<h3>` details blocks.

2. **Semantic Landmark Migration (`<div>` to Component Blocks):**
   * *Before:* Generic structural containers were used to bundle navigation blocks, standalone updates, and site metadata.
   * *After:* Upgraded the layout structure using high-value semantic elements (`<nav>`, `<main>`, `<article>`, and `<footer>`) to create distinct screen reader landmarks.

3. **Fragment Target Association:**
   * Bound structural page anchor jumps directly to matching article `id` indicators, establishing flawless skip-navigation behavior loops.