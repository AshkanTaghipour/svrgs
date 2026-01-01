# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

SVR-GS (Spatially Variant Regularization for 3D Gaussian Splatting) is a static HTML academic project page. It presents research on optimizing 3D Gaussian Splatting through spatially variant regularization of probabilistic masks.

## Development

This is a static website with no build system. To develop locally:

```bash
# Serve locally with any HTTP server, e.g.:
python -m http.server 8000
# or
npx serve .
```

Open `http://localhost:8000` in a browser.

## Architecture

- **index.html** - Single-page project site with hero, abstract, method diagram, and visual results sections
- **static/css/** - Bulma framework + custom styles in `index.css`
- **static/js/** - jQuery-based interactivity for image slider/carousel in `index.js`
- **static/diagrams/** - Method overview diagrams
- **static/videos/** - Demo video content
- **static/interpolation/stacked/** - 240 interpolation frame images for slider

## Key Dependencies (CDN/Local)

- Bulma CSS framework (local, minified)
- FontAwesome icons (local)
- Academic Icons (CDN) for arXiv links
- Google Fonts (CDN): Google Sans, Noto Sans, Castoro

## Code Style

- Do not use comments in this codebase

## Template

Based on the [Nerfies](https://nerfies.github.io) academic project page template. Licensed under Creative Commons Attribution-ShareAlike 4.0 International.
