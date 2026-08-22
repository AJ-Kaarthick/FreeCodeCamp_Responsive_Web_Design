# ♠️ Project 20: Playing Cards Layout Page

A responsive playing card display built with CSS Flexbox alignment mechanics (`align-self`), card layout structure, and flex wrapping.

## 🛠️ Key Architectural Concepts Mastered

1. **Individual Flex Item Alignment (`align-self`):**
   * Applied `align-self: flex-start`, `align-self: center`, and `align-self: flex-end` across top-left, center, and bottom-right card sections within a single flex parent.

2. **Nested Flexbox Containers:**
   * Combined horizontal container flex (`display: flex`, `justify-content: space-between`) with vertical internal stacking (`flex-direction: column` in `.middle`) to build authentic playing card layouts.

3. **Responsive Grid Wrapping & Spacing:**
   * Configured `#playing-cards` parent with `flex-wrap: wrap` and `gap: 20px` to maintain responsive card grids across screen sizes.