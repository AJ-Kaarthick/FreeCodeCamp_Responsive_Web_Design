# 📰 Project 22: Newspaper Article

An independent print-editorial layout project practicing typography units (`rem` vs `em`), root font scaling, text transformation rules, and drop-cap styling using the `::first-letter` pseudo-element.

## 🛠️ Key Architectural Concepts Mastered

1. **Relative Font Scaling (`rem` vs `em`):**
   * Scaled elements relative to the root (`2rem` on 24px `html`) vs relative to parent containers (`2em` and `1.5em` on `.newspaper`).

2. **Drop-Cap Pseudo-Elements (`::first-letter`):**
   * Created classical newspaper drop-caps using `.text::first-letter` with explicit `font-weight: bold`, `font-style: italic`, and doubled font sizing.

3. **Editorial Typography & Indentation:**
   * Managed traditional print styling using `text-transform: uppercase`, paragraph `text-indent: 20px`, proportional `line-height: 2em`, and serif heading fallbacks.