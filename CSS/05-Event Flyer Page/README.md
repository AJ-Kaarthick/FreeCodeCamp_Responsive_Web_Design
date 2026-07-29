# 🎟️ Project 05: Event Flyer Page

An independent responsive CSS document practicing viewport-based sizing (`vw`, `vh`), viewport-aware layout math using `calc()`, semantic layout structures (`header`, `main`, `section`), and relative component percentage constraints.

## 🛠️ Key Architectural Constraints Mastered

1. **Viewport Calculation & Layout Math:**
   * Utilized CSS `calc()` to dynamically establish minimum document bounds (`min-height: calc(100vh - 100px);`) derived from viewport height offsetting top/bottom padding values.

2. **Viewport-Relative Responsive Sizing:**
   * Configured primary document container widths relative to the viewport scale (`width: 80vw;`) with centered margin auto-alignment (`margin-left: auto; margin-right: auto;`).

3. **Relative Percentage Child Constraints:**
   * Restricted horizontal structural dividers (`hr`) and semantic content sections (`section`) using percentage bounds (`width: 90%;`) relative to parent container block boxes.