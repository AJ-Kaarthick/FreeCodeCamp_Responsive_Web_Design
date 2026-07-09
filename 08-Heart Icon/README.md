🎨 Workshop 08: Heart Icon Page

This project is a clean, structured graphics layout built to explore vector rendering capabilities using native inline SVG elements.
📝 Project Description

The Heart Icon Page focuses on rendering scalable vector graphics directly within the HTML document structure without relying on external image files (like .png or .jpg). It demonstrates how to utilize direct coordinate plotting data, fill properties, and viewport scaling to construct a sharp, lightweight UI component designed for instant browser rendering.
🧠 Core Technical Takeaways

    Inline Vector Rendering: Implemented the semantic <svg> element to inject lightweight, resolution-independent math graphics directly into the DOM tree.

    Coordinate Space Optimization: Utilized the viewBox="0 0 24 24" attribute to define an isolated aspect ratio and coordinate system grid for precise component scaling.

    Complex Path Plotting: Explored vector path tracing using the <path> element's d (draw) attribute to execute complex cubic bezier curves and coordinate commands.

🛠️ Code Snippet Spotlight

Here is how the inline vector graphic was structured using path data and viewport configurations to ensure scaling accuracy and proper fill rendering:

<svg width="24" height="24" viewBox="0 0 24 24" fill="red"> 
  <path 
    d="M12 21s-6-4.35-9.33-8.22C-.5 7.39 3.24 1 8.4 4.28 10.08 5.32 12 7.5 12 7.5s1.92-2.18 3.6-3.22C20.76 1 24.5 7.39 21.33 12.78 18 16.65 12 21 12 21z" 
  ></path> 
</svg>