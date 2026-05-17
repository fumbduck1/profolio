# Site-ready static pages

This folder contains a minimal static, multi-page portfolio for Akram Hossain. Files:

- `index.html` — Home (landing, stack, metrics)
- `about.html` — Soft skills / About
- `projects.html` — Featured projects (trimmed to requested items)
- `contact.html` — Contact + CV preview and download

How to use

1. Host the `site/` folder on any static host (GitHub Pages, Netlify, Vercel, static S3, etc.).
2. To embed in Google Sites, publish the site publicly and use Insert → Embed → By URL with the page URL (e.g., `https://yourdomain.com/index.html`).

Notes

- The site uses relative links for route navigation (standard HTML pages). This avoids client-side routing issues when embedded.
- If you prefer a single-file embed for Google Sites, embed the specific page (for example, `contact.html`) using its hosted URL.
