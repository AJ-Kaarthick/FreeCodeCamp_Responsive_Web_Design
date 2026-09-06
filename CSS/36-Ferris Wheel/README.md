# 🎡 Project 36: Ferris Wheel

An animated CSS graphics project demonstrating `@keyframes` rules, continuous infinite rotation, transform origin manipulation, and synchronized counter-rotation effects.

## 🛠️ Key Architectural Concepts Mastered

1. **CSS `@keyframes` Animations:**
   * Constructed continuous linear rotation for the wheel structure and timed color/transform state changes for attached cabins.

2. **Counter-Rotation Technique:**
   * Applied inverse rotational keyframes (`-360deg`) to individual cabins to maintain an upright orientation while the parent structure rotates.

3. **Origin & Layout Positioning (`transform-origin`):**
   * Configured absolute rotational origins (`0% 0%` and `50% 0%`) combined with `:nth-of-type` selectors to position spokes and cabins symmetrically across a 360-degree circle.