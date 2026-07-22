# ☕ Workshop 01: Cafe Menu

An introduction to fundamental CSS styling principles, box model manipulations, typography customization, and external stylesheet linking.

## 🛠️ Key Architectural Concepts Explored

1. **External Stylesheet Association (`<link>`):**
   * Linked external style sheets cleanly to HTML documents using standard `<link href="styles.css" rel="stylesheet"/>` tags to strictly separate structure from presentational logic.

2. **The CSS Box Model (`margin`, `padding`, `width`):**
   * Managed container boundaries using `max-width: 500px` paired with `margin-left: auto` and `margin-right: auto` to easily center block layout components.

3. **Inline-Block Layout Flow (`display: inline-block`):**
   * Structured menu item lines side-by-side using percentage-based widths (`75%` for titles and `25%` for prices) rendered inline to build aligned dynamic menu rows.

4. **Pseudo-Class Anchor States (`:hover`, `:visited`, `:active`):**
   * Configured interactive pseudo-selectors to control anchor element color states across active user interactions.