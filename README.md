# MUFAASH Health Services website

A responsive, accessible, static marketing website for MUFAASH Health Services.

## Features
- Mobile-first responsive layout and accessible mobile navigation
- Services overview, equipment portfolio (12 image cards), company profile and three office locations
- Equipment category filters
- Scroll-reveal motion, hover transitions and reduced-motion support
- Direct phone, email, WhatsApp and map-search links
- Semantic HTML, descriptive image alternatives, skip link and page metadata
- No framework or build step required

## Run locally
Open `index.html` in a browser, or serve the folder with any static web server, for example:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Project structure
- `index.html` — page structure and content
- `styles.css` — responsive design system, layout and motion
- `script.js` — navigation, equipment filters and progressive enhancement
- `assets/mufaash-logo.svg` — vector logo artwork recreated from the supplied visual reference

## Notes
Equipment photos are loaded from Unsplash over HTTPS and require an internet connection. The portfolio images are illustrative; they do not represent confirmed stock or specific models available from MUFAASH. Verify product details and service availability directly with the company.

Contact details and office addresses are displayed as supplied. The site does not collect or store visitor data.
