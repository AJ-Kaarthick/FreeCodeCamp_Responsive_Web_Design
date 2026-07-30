# 🎂 Project: Greeting Card

A CSS interaction and state management project demonstrating target-based section toggling (`:target`), pseudo-elements (`::before`, `::after`), flexbox positioning, transitions, and pseudo-class state cascades (`:hover`, `:active`, `:focus`, `:visited`).

## 🛠️ Key Concepts Mastered

1. **Target-Based Navigation (`:target`):**
   * Configured dynamic section display toggles using pure CSS (`section { display: none; }` and `section:target { display: block; }`) bound to anchor fragment URIs (`#send`, `#share`).

2. **Pseudo-Elements (`::before`, `::after`):**
   * Generated decorative text emoji accents on the `h1` header directly via CSS using `content: "🥳 "`.

3. **Smooth Interactive Transitions & Transforms:**
   * Applied hover scaling (`transform: scale(1.1)`), background color transitions (`transition: 0.3s ease`), and skew transforms (`transform: skewX(10deg)`).

4. **Anchor Pseudo-Class State Cascade:**
   * Implemented custom state styling for active interactions (`:hover`, `:active`), keyboard navigation accessibility (`:focus`), and link history (`:visited`).