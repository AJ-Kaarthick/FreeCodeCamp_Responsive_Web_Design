# 📰 Project 35: Newspaper Layout

A classic multi-column front-page newspaper layout built with explicit CSS Grid template areas, auto/fractional track sizes, and structured typography.

## 🛠️ Key Architectural Concepts Mastered

1. **Named Grid Template Areas (`grid-template-areas`):**
   * Mapped complex editorial layouts across multi-column rows using named grid regions like `title`, `feature-article`, `cover-image`, and `secondary-article`.

2. **Explicit Track Sizing (`grid-template-columns`, `grid-template-rows`):**
   * Configured three equal-width fractional columns (`1fr 1fr 1fr`) paired with structured row sizing (`auto 1fr 1fr 1fr`).

3. **Media Bounds Constraints (`max-width: 100%`):**
   * Restricted the cover image within its assigned grid area while keeping layout bounds intact.