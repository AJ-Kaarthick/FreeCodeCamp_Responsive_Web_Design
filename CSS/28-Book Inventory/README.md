# 📚 Project 28: Book Inventory

A certification project demonstrating advanced CSS attribute selectors (`~=`, `^=`, `*=`), structural table markup, customized linear gradient themes, and custom indicator components.

## 🛠️ Key Architectural Concepts Mastered

1. **Exact Word Attribute Selectors (`~=`):**
   * Leveraged `span[class~="one"]`, `span[class~="two"]`, and `span[class~="three"]` to target space-separated class values cleanly and satisfy strict test suites.

2. **Attribute Substring Selectors (`^=`):**
   * Applied prefix matching (`span[class^="rate"]`) to dynamically style container dimensions and layout for rating elements regardless of their rating value class.

3. **Custom Rating Indicator Component:**
   * Built a pure CSS dot-rating indicator system combining attribute selectors with structural pseudo-classes (`:nth-child(1)`, `:nth-child(2)`).

4. **Status-Driven Dynamic Styling:**
   * Styled state-specific table rows (`.read`, `.to-read`, `.in-progress`) using custom linear gradients and accessible status badge highlights.