# 📊 Project 27: Balance Sheet

A curriculum web accessibility and complex tabular layout project building a financial balance sheet using semantic HTML `<table>` elements, sticky column headers, pseudo-element text wrappers, and screen-reader accessibility hacks.

## 🛠️ Key Architectural Concepts Mastered

1. **Accessible Screen Reader Utility (`sr-only`):**
   * Implemented custom `.sr-only` CSS clipping patterns (`clip: rect(...)`, `clip-path: inset(50%)`) to visually hide table headers while preserving complete context for screen readers.

2. **Sticky Table Navigation:**
   * Utilized `position: sticky` and high `z-index` layering on `#years` to keep annual financial columns pinned while scrolling through table data sections.

3. **Complex Tabular Styling & Alignment:**
   * Styled structured tables using `border-collapse: collapse`, calculated percentage widths (`calc()`), `caption` positioning, double-line financial borders (`border-bottom: 4px double`), and multi-stop `linear-gradient` backgrounds for row styling.