# 📋 Project 07: Parent Teacher Conference Form

A semantic HTML5 form styling project focusing on fieldset grouping, `:not()` functional pseudo-class selection, custom-styled radio buttons with pseudo-elements (`::before`), and responsive container bounds.

## 🛠️ Key Concepts Mastered

1. **Custom Form Controls & Pseudo-Elements (`::before`):**
   * Overrode native radio styling using `appearance: none` to build a custom interactive radio button with animated selection dots (`transform: scale(1)` + `transition`).

2. **Negative Pseudo-Class Selection (`:not()`):**
   * Efficiently styled form fields and label layouts by excluding inline controls via `:not(.contact-method)` and `input:not(.contact-method-radio-btn)`.

3. **Semi-Transparent Layering (`RGBA` / Hex Alpha):**
   * Applied `#ffffff1a` (10% opacity white) across containers, inputs, and textareas to create dark-mode glassmorphism aesthetics against the `MidnightBlue` body background.

4. **Accessible Placeholder Styling (`::placeholder`):**
   * Explicitly set contrast colors on placeholder text strings using `input::placeholder` to maintain readability against dark input fields.