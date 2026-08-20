# 🎮 Project 13: Game Settings Panel

A UI card component demonstrating custom checkbox form controls using `appearance: none`, `:checked` pseudo-class states, pseudo-elements (`::after`), and smooth visual transitions.

## 🛠️ Key Concepts Mastered

1. **Custom Checkbox UI Overrides (`appearance: none`):**
   * Suppressed default browser input styles using `appearance: none` to build a custom square checkbox with rounded borders (`border-radius: 4px`).

2. **Pseudo-Element Checkmarks (`::after`):**
   * Generated checkmark icons inside checked boxes dynamically using `input[type="checkbox"]:checked::after` with Unicode content (`✓`) and centered line height.

3. **Interactive Control States (`:checked`):**
   * Updated background fills and border colors seamlessly when options are toggled on using `:checked` pseudo-class selectors.