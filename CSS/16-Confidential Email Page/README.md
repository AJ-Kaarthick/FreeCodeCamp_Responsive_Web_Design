# 🔒 Project 16: Confidential Email Page

An independent classified document UI application practicing precise box model width calculations (`box-sizing: border-box`), text redaction effects (`filter: blur()`), inline-block layout positioning, and rotation transformations (`transform: rotate()`).

## 🛠️ Key Architectural Concepts Mastered

1. **Strict Box Model Width Calculation:**
   * Managed container boundaries explicitly using `box-sizing: border-box`, ensuring total element width (including 50px padding and 2px border) remains exactly 500px.

2. **Text Redaction & Filters (`filter: blur()`):**
   * Applied CSS Gaussian blur filters (`filter: blur(3px)`) to inline `<span>` elements to simulate redacted sensitive information within text paragraphs.

3. **Stamp Badge Transformations:**
   * Created stamp overlay badges using `display: inline-block`, custom borders, and rotation transforms (`transform: rotate()`) to render angled classification marks.