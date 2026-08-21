# 💳 Project 19: Pricing Plans Layout Page

An independent responsive pricing component built with CSS Flexbox, featuring explicit flex item ordering (`order`), dynamic container expansion (`flex-grow: 2`), custom feature checklists, and direct-child element column alignment.

## 🛠️ Key Architectural Concepts Mastered

1. **Flex Item Ordering (`order`):**
   * Configured explicit visual ordering (`order: 0`, `order: 1`, `order: 2`) across pricing tiers independently of HTML source structure.

2. **Flex Sizing & Expansion Controls (`flex-grow`):**
   * Constrained card bases (`flex: 0 0 200px`) while allowing featured plans (`.pro-plan`) to expand dynamically across available container space using `flex-grow: 2`.

3. **Flex Column Spacing (`justify-content: space-between`):**
   * Enforced vertical stacking (`flex-direction: column`) within pricing cards, distributing header text, price tags, feature lists, and CTA buttons cleanly using `space-between`.