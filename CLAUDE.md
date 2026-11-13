# Project Overview
This is a personal portfolio for a computational physicist, visual artist, and photographer. 
It is hosted on GitHub Pages as a static site. 

# Tech Stack & Constraints
- Frontend ONLY: HTML, CSS, vanilla JavaScript, and p5.js.
- NO backend code, NO Node.js, NO React/Vue, NO build steps or bundlers.
- Keep the code lightweight. 

# Media & Storage Rules
- Do NOT add large image or video files directly to this repository (GitHub Pages has a 1GB limit).
- For local development, use low-res placeholders in an `/assets` folder.
- In production, heavy media will be hosted externally (e.g., Cloudflare R2) and embedded via URLs.

# Privacy & Security
- Preserve AI scraper blocking tags (`<meta name="robots" content="noai, noimageai">`) in all HTML files.
- Preserve the `robots.txt` file blocking AI crawlers.
- Ensure any photo metadata or C2PA credentials remain intact if writing scripts to process images.

# Workflow
- The `main` branch is production. 
- Always create a new feature branch for layout changes or p5.js experiments before modifying `main`.