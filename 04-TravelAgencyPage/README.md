# ✈️ Workshop 04: Travel Agency Page

This project is a clean, structured travel destination showcase built to satisfy the structural and SEO requirements of the freeCodeCamp curriculum.

## 📝 Project Description
The Travel Agency Page focuses on standard semantic HTML layouts, basic search engine optimization via metadata, and handling nested interactive elements. Instead of using default testing placeholders, this version uses custom, descriptive text layouts and individual asset links to build a unique gallery of top itineraries.

## 🧠 Core Technical Takeaways
* **SEO Metadata Incorporation:** Implemented a targeted page description using a secondary `<meta>` element inside the document head to handle search engine discovery.
* **Complex Anchor Nesting:** Practiced structural nesting by completely wrapping text blocks inside list items and wrapping full inline `<img>` blocks inside individual anchor links (`<a>`).
* **Semantic Media Figures:** Organized visual cards using independent `<figure>` elements paired with nested `<figcaption>` text blocks to properly align media assets with their readable descriptions.

## 🛠️ Code Snippet Spotlight
Here is how the image link layout was cleanly structured within semantic figures to ensure valid nesting and smooth test execution:

```html
<figure>
  <a href="https://www.freecodecamp.org/learn" target="_blank">
    <img src="https://images.unsplash.com/photo-1552832230-c0197dd311b5?w=600&auto=format&fit=crop&q=80" alt="The historic Roman Colosseum under a blue sky." />
  </a>
  <figcaption>Explore the ancient history and rich heritage of Rome, Italy.</figcaption>
</figure>