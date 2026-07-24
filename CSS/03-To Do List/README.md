# 📝 Project 03: To-Do List

An independent responsive CSS task interface practicing complete link pseudo-class state management (`:link`, `:visited`, `:hover`, `:active`, `:focus`), form label associations, and nested document list hierarchies.

## 🛠️ Key Architectural Constraints Mastered

1. **Sequential Pseudo-Class State Cascade (LVHA Rule):**
   * Configured anchor state declarations strictly matching standard ordering logic (`:link` -> `:visited` -> `:hover` -> `:active`) to ensure predictable color cascading across interactive link lifecycles.

2. **Accessibility Outline Management (`:focus`):**
   * Implemented explicit focus indicators (`outline: 2px dashed #00897b`) on keyboard-focused elements to maintain accessible navigation compliance.

3. **Semantic Form & List Nesting Structures:**
   * Connected form input checkboxes directly to companion label elements using matching `id` and `for` attributes, while embedding nested sub-item unordered lists (`ul.sub-item`) cleanly within parent task items.