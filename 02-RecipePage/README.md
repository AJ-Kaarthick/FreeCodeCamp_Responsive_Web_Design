# 🥞 Workshop 02: Recipe Page

This project is a standalone recipe webpage built to fulfill the core structural requirements of the freeCodeCamp Responsive Web Design curriculum. It showcases a classic recipe with proper text, media, and list formatting.

## 📝 Project Description
The Recipe Page focuses on content organization and proper use of distinct list styles. Instead of the default template, this page features a custom **Classic Chicken Biryani** recipe, demonstrating how to handle independent asset images alongside strict text layouts required by technical test suites.

## 🧠 Core Technical Takeaways
* **Headings Hierarchy:** Maintained a clean layout by using a single semantic `<h1>` for the main title and multiple `<h2>` elements to break up major sections.
* **Mixed List Layouts:** Implemented an unordered list (`<ul>`) for individual ingredient components where sequence doesn't matter, and an ordered list (`<ol>`) to track sequential step-by-step cooking instructions.
* **Custom Media Optimization:** Swapped the generic course image with a high-quality, external Unsplash CDN graphic while maintaining accurate, accessible descriptive `alt` text for web readers.

## 🛠️ Code Snippet Spotlight
Here is how the sequential instructions were structured using an ordered list to ensure step numbers render automatically:

```html
<h2>Instructions</h2>
<ol>
  <li>Marinate the chicken with yogurt, biryani masala spices, and half of the fried onions for at least one hour.</li>
  <li>Wash and soak the rice, then boil it in a large pot of salted water until it is 70% cooked.</li>
</ol>
