# ananthusworld.github.io

## Repository Overview

This repository hosts a single-page, static personal website focused on Site Reliability Engineering (SRE), mobile reliability, and professional portfolio content.

### What is in this repo
- `index.html`: the complete website (HTML structure, embedded CSS, and JavaScript).
- Static assets referenced by the page:
  - `hero.png` (hero banner)
  - `profile.jpg` (profile image)
  - `resume.pdf` (downloadable resume)
  - company logo images (`macys.jpg`, `apple.jpg`, `zylog.jpg`, `cognizant.jpg`)

### How the page is organized
The single HTML file is split into clear sections that render a scrolling profile experience:
- Intro/hero and SRE explainer
- Mobile SRE deep-dive content
- External learning/blog links
- Profile and work history
- Projects, skills, education, certifications, and awards
- About and contact links

### Technology stack
- **HTML5** for layout/content
- **Embedded CSS** for styling and responsive behavior
- **Vanilla JavaScript** for mobile navigation interactions
- **External CDNs** for:
  - Google Fonts (`Poppins`)
  - Font Awesome icons
  - ScrollReveal animation library

### Local development
Because this is a static site, you can run it locally with any simple HTTP server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

### Deployment model
This repo is structured for static hosting (e.g., GitHub Pages), where `index.html` acts as the site entry point.
