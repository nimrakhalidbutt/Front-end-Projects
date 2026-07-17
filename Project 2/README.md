# Wren & Ashby — Luxury Watch Brand Website

## Description

A single-page marketing website for **Wren & Ashby**, a fictional heritage watchmaker brand. The site is designed with an "old money" aesthetic — bottle green, parchment cream, and aged brass tones — and focuses on rich, interactive product presentation rather than static photos.

Key features:
- Hero section with a **live, ticking SVG watch** that tracks real time and tilts in 3D on cursor movement
- A drag-to-scroll **collection gallery** of five watch pieces, each an interactive SVG with hover-tilt
- Scroll-triggered reveal animations throughout
- A condensing navigation bar and mobile slide-out menu
- Fully responsive layout (desktop, tablet, mobile)
- Respects `prefers-reduced-motion` for accessibility

Built with plain HTML, CSS, and JavaScript — no build tools, frameworks, or dependencies required (only Google Fonts loaded via CDN).

## How to Run

No installation or build step is needed — it's a single static HTML file.

**Option 1: Open directly**
Double-click `index.html`, or open it from your browser:
```
open index.html        # macOS
start index.html        # Windows
xdg-open index.html     # Linux
```

**Option 2: Run a local server (recommended for full functionality)**
Serving over `http://localhost` avoids any browser restrictions on local files:
```bash
# Python 3
python3 -m http.server 8000

# Node (with npx)
npx serve .
```
Then visit `http://localhost:8000` in your browser.

## File Structure

```
index.html   # Complete site — HTML, CSS, and JS in one file
README.md    # This file
```