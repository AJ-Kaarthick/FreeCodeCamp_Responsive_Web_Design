🐾 Workshop 13: Cat Blog Page

This project is a complete, structured blogging layout built to explore semantic page layout landmarks, internal page navigation, and formal contact protocols in HTML5.
📝 Project Description

The Cat Blog Page focuses on building a multi-section document architecture using foundational layout elements. This project implements a fully functional header navigation menu that jumps to targeted internal section identifiers, structures standalone blog entries with isolated article semantics, and incorporates a standard footer with clickable communication shortcuts.
🧠 Core Technical Takeaways

    Internal Anchor Navigation: Configured localized navigation links utilizing fragment identifiers (href="#about") mapped to matching section target IDs to enable instant, single-page jumping.

    Independent Article Encapsulation: Practiced syndication layouts by wrapping separate blog entries within standalone <article> containers, separating content blocks from the main document scope.

    Communication Protocol Links: Implemented active communication channels inside a semantic <address> block using mailto: for instant email routing and tel: for native mobile dialing protocols.

🛠️ Code Snippet Spotlight

Here is how the document structure and contact details were cleanly segmented inside semantic landmark boundaries:

<footer> 
  <section id="contact"> 
    <h2>Contact</h2> 
    <address> 
      <p>Phone: <a href="tel:5555555555">555-555-5555</a></p> 
      <p>Email: <a href="mailto:fake@email.com">fake@email.com</a></p> 
    </address> 
  </section> 
</footer>