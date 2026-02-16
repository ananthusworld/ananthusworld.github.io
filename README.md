# ananthusworld.github.io

## Repository Overview

This repository hosts a static personal website focused on Site Reliability Engineering (SRE), mobile reliability, and professional portfolio content.

## What is in this repo
- `index.html`: primary site entry point.
- Deep-dive article pages (for SRE and mobile reliability topics):
  - `mobile-sre-native-app.html`
  - `sre-artificial-intelligence.html`
  - `sre-error-budgets.html`
  - `sre-maturity-levels.html`
  - `sre-predictive-detection.html`
  - `sre-self-healing-systems.html`
  - `sre-us-online-retail-holiday-traffic.html`
- Shared static assets by type:
  - `assets/css/article.css` (reusable style sheet for article pages)
  - `assets/images/` (hero, profile, company logos, architecture diagrams)
  - `assets/docs/resume.pdf`

## Structure and reusability
- Article pages use a shared stylesheet (`assets/css/article.css`) to avoid repeated inline CSS.
- Images and documents are grouped by file type under `assets/` for easier maintenance and consistent linking.
- `index.html` and article pages reference assets via `assets/...` paths suitable for static hosting (for example, GitHub Pages).

## Technology stack
- **HTML5** for layout/content
- **CSS3** (shared stylesheet for articles + page-specific styles)
- **Vanilla JavaScript** for interactions in `index.html`
- **External CDNs** for:
  - Google Fonts (`Poppins` for main page, `Roboto` for article pages)
  - Font Awesome icons
  - ScrollReveal animation library

## Local development
Because this is a static site, you can run it locally with any simple HTTP server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Deployment model
This repo is structured for static hosting (for example, GitHub Pages), where `index.html` acts as the site entry point.
