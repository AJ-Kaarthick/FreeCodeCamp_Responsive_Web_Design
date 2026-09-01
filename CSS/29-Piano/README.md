# 🎹 Project 29: Piano

A curriculum CSS layout and responsive design project building an interactive-style piano keyboard using CSS pseudo-elements, positioning, floating elements, and media query breakpoints.

## 🛠️ Key Architectural Concepts Mastered

1. **Pseudo-Element Component Layering (`::after`):**
   * Constructed black piano keys over white key elements using `.key.black--key::after` pseudo-elements positioned absolutely relative to parent keys.

2. **Responsive Breakpoints via Media Queries:**
   * Applied `@media (max-width: 768px)` and combined range query `@media (max-width: 1199px) and (min-width: 769px)` to dynamically scale piano container and key boundaries across screen sizes.

3. **Box Sizing & Element Alignment:**
   * Configured global `box-sizing: border-box` alongside CSS `float: left` layouts to ensure key margins, padding, and widths stay perfectly aligned inside the piano casing.