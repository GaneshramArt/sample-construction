# Sample Construction — Website

A luxury three-page website for **Sample Construction**, a real estate and construction company.

**Pages:** Home · Projects · Contact. All three live in `index.html` and switch through hash links (`#/`, `#/projects`, `#/contact`).

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
# or
python -m http.server 8000
```

## Structure

```
index.html        All pages, styles and scripts
assets/           Optimised images, hero film (hero.mp4) and showreel (reel.mp4)
docs/             Product Requirements Document (PRD)
```

## Features

- Full-screen video hero, before/after construction slider, six-stage process, materials section
- Filterable project portfolio with detail pop-ups
- Enquiry form with validation, visit booking fields, WhatsApp button
- Responsive from 360 px to 2560 px, reduced-motion support, keyboard accessible

## Before going live

- Replace placeholder content: project names, prices, statistics, phone numbers, address and RERA number.
- Connect the enquiry form to email or a CRM (it currently shows a confirmation message only).
- Replace or label AI-generated renders; all images are currently marked "Artist's impression".

## Deploy

Static site — works on GitHub Pages, Vercel or Netlify with no build step.
For GitHub Pages: *Settings → Pages → Deploy from branch → `main` / root*.
