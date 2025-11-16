# mlPracticeProj

Lightweight front-end app to generate and visualize a 2D classification dataset where red points form a ring encircling blue points. No frameworks; a single `index.html` in the repo root.

## Quick Start

- Option 1: Open `index.html` directly in your browser.
- Option 2 (recommended): serve locally to ensure crisp canvas sizing and avoid any browser security quirks.

```bash
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

Use the sliders to control counts, inner spread, ring radius/thickness, and label noise. Click Regenerate to draw a fresh sample; Export JSON downloads the current dataset for later training.