🎬 Workshop 07: Media Lab Page

This project is a clean, structured multimedia showcase built to explore the side-by-side integration of native HTML5 audio and video layouts within independent page sections.
📝 Project Description

The Media Lab Page focuses on organizing distinct audio and video components using semantic layout containers. Instead of isolating single media types, this project implements a unified gallery format that combines direct browser-native video rendering with custom background looping audio configurations, creating an immersive semantic layout.
🧠 Core Technical Takeaways

    Dual-Media Layout Organization: Practiced semantic partitioning by separating the independent video and audio media player zones into designated layout wrappers (<section>).

    Direct Multimedia Sourcing: Configured direct web asset integration for both video components (video/mp4) and standard audio tracks (audio/mp3) using secure, external CDN pathways.

    Control UI Configurations: Applied native user interface elements including visual dimensions (width="640"), default browser controllers (controls), and automated tracking replays (loop) to balance media behavior and structure.

🛠️ Code Snippet Spotlight

Here is how the dual media player channels were cleanly organized using independent semantic sections to ensure standalone, valid nesting:

<section>
  <h2>Beautiful Nature</h2>
  <video width="640" controls>
    <source src="https://interactive-examples.mdn.mozilla.net/media/cc0-videos/flower.mp4" type="video/mp4">
  </video>
</section>

<section>
  <h2>Horse sounds</h2>
  <audio controls loop src="https://www.w3schools.com/html/horse.mp3"></audio>
</section>