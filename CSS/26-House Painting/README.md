# 🏠 Project 26: House Painting

An independent CSS project building a structured house and landscape using absolute element positioning relative to container boundaries, `z-index` stacking, Flexbox alignment, and CSS linear gradients.

## 🛠️ Key Architectural Concepts Mastered

1. **Relative vs. Absolute Coordinate Framing:**
   * Configured `#house` with `position: relative` to create a local coordinate system, allowing child elements (`#roof`, `#door`, `#window-1`, `#window-2`, `#chimney`) to position using precise `top`, `bottom`, `left`, and `right` offsets.

2. **Landscape Environment with CSS Gradients:**
   * Designed a sky and ground environment using `linear-gradient(to bottom, ...)` with hard stop percentages (`75%`), dividing the background without extra HTML markup.

3. **Flexbox Viewport Placement:**
   * Utilized `display: flex`, `justify-content: center`, and `align-items: flex-end` on the document body to lock the house centrally onto the ground horizon.

4. **Stacking Context (`z-index`):**
   * Placed `#chimney` behind the primary house structure using `z-index: -1` while aligning its top offset (`top: 0`) to the top edge of the `#house` boundary.