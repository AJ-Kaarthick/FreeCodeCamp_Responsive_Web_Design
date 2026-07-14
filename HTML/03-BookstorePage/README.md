# 📚 Workshop 03: Bookstore Page

This project focuses on styling structured application layouts using containers and custom styling targets. It acts as an introduction to component isolation within a web layout.

## 📝 Project Description
The Bookstore Page establishes a foundational grid or flex card container layout. It features specialized product groupings containing custom descriptions and clear actionable utility buttons (`Buy Now`, `View Cart`, `Checkout`).

## 🧠 Core Technical Takeaways
* **Component Container Division:** Practiced layout scoping by wrapping item elements inside designated parent wrappers (`card-container` and `btn-container`).
* **Identity vs Group Selectors:** Explored organizing elements globally via class declarations (`class="card"`) while maintaining specific structural target hooks via attributes (`id="sally-adventure-book"`).

🛠️ Code Snippet Spotlight

Here is how the independent product card components were cleanly structured using global styling classes and unique identity hooks to ensure precise layout isolation:

<div class="card-container">
  <div class="card" id="sally-adventure-book">
    <h2>Sally's SciFi Adventure</h2>
    <p>This is an epic story of Sally and her dog Rex as they navigate through other worlds.</p>
    <button class="btn">Buy Now</button>
  </div>
</div>