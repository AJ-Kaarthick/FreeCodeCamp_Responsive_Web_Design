# ♿ Project 23: Accessibility Quiz

A web accessibility practice project implementing ARIA landmarks, screen reader styling (`.sr-only`), keyboard navigation, semantic form controls, dynamic CSS sizing functions (`min()`, `max()`), and motion preferences.

## 🛠️ Key Concepts Mastered

1. **Accessibility & ARIA Standards:**
   * Utilized ARIA region roles (`role="region"`), explicit labeling (`aria-labelledby`), semantic `<fieldset>`/`<legend>` elements, and absolute screen-reader utility classes (`.sr-only`).

2. **Responsive CSS Sizing Functions:**
   * Applied `min(5vw, 1.2em)` and `max(10rem, 18vw)` alongside `aspect-ratio` to maintain responsive scaling across typography and media without breaking UI boundaries.

3. **User Preference Media Queries:**
   * Implemented `@media (prefers-reduced-motion: no-preference)` to respect user OS accessibility settings regarding smooth scrolling animations.