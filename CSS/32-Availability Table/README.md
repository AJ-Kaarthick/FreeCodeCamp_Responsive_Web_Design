# 📅 Project 32: Availability Table

An accessible heat-map style scheduling application featuring structured table elements, custom CSS variables, hard-stop linear gradients, and row-level border patterns.

## 🛠️ Key Architectural Concepts Mastered

1. **Accessibility Scoping & Attributes (`scope`, `aria-label`):**
   * Configured explicit table structure using `scope="col"` and `scope="row"` headers alongside assistive `aria-label` descriptions for heat-map values.

2. **CSS Variables & Custom Palettes (`:root`):**
   * Defined dynamic palette variables (`--color0` through `--color5`) to map intensity scales directly to data cell background colors.

3. **Hard-Stop Linear Gradients:**
   * Constructed discrete color segment legends using percentage hard stops inside `linear-gradient()`.

4. **Alternating Row Borders:**
   * Applied contextual border variables (`--solid-border` and `--dashed-border`) across `.sharp` and `.half` table rows.