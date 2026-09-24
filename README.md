# Nkemdi Onwordi — Personal Portfolio Website

A personal portfolio and ideas website for **Nkemdi Patrick Onwordi**, Digital Product Manager and Senior Product/Solution Owner at OFGEM. Built as a single, self-contained static HTML file — no build tools, frameworks, or backend required.

🔗 **Live site:** _add your deployed URL here once published (e.g. via GitHub Pages or Netlify)_

---

## About

This site showcases Nkemdi's professional background, ideas and writing, event gallery, and contact information, with a tech/energy/charity-inspired visual theme.

## Features

- **Home** — Blog-style feed for published articles and ideas
- **Meet Me** — Professional bio, background, certifications, and career highlights
- **Gallery & Events** — Photo gallery of team events and milestones
- **Upcoming Events** — Event list plus a monthly calendar view
- **Contact** — Email, phone, location, social links, and an embedded GPS map (OpenStreetMap)
- **Live World Clock** — Real-time clocks for the UK (auto-adjusts for BST/GMT) and Nigeria (WAT)
- **Footer** — Quick navigation links, contact details, and copyright/funding notice
- Dark, animated tech-inspired background (gradient orbs, grid overlay, floating particles)
- Fully responsive layout

## Tech Stack

- Plain **HTML5, CSS3, and vanilla JavaScript**
- No frameworks, no build step, no dependencies
- Map embed via [OpenStreetMap](https://www.openstreetmap.org/)
- Gallery images via [Unsplash](https://unsplash.com/) placeholders (replace with your own photos)

## Project Structure

```
├── index.html # Entire site — markup, styles, and logic in one file
└── README.md # This file
```

## Running Locally

No installation needed. Either:

1. Double-click `index.html` to open it directly in your browser, **or**
2. Serve it locally for a closer-to-production feel:
   ```bash
   npx serve .
   # or
   python3 -m http.server 8000
   ```
   Then visit `http://localhost:8000` (or the port shown).

## Deployment

### Option A — GitHub Pages
1. Push `index.html` to this repository's default branch.
2. Go to **Settings → Pages**.
3. Set source to the default branch, root folder.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

### Option B — Netlify Drop
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag `index.html` into the browser window.
3. Get an instant live URL (custom subdomain optional).

## Customising Content

All content is hard-coded directly in `index.html` for simplicity and reliability:

| Section | Where to edit |
|---|---|
| Bio / About Me | `#tab-meet` section |
| Blog posts | `posts` array in the `<script>` block |
| Gallery images | `gallery` array in the `<script>` block |
| Upcoming events | `events` array in the `<script>` block |
| Contact details & social links | `#tab-contact` section and `<footer>` |
| Map location | `latitude`/`longitude` values in the map `iframe` `src` |

> Note: This static version has no backend or database, so edits must be made directly in the code and redeployed — there is no in-browser "Edit" or "Save" functionality.

## Contact

- **Email:** onwordi.nkemdi@gmail.com
- **Phone:** 07901032385
- **Location:** Middlesbrough, United Kingdom
- **LinkedIn:** [linkedin.com/in/nkemdi-onwordi-7a095329](https://www.linkedin.com/in/nkemdi-onwordi-7a095329)
- **GitHub:** [github.com/omosuyi](https://github.com/omosuyi/onwordi.github.io)

## License & Attribution

© 2026 Onwordi. All rights reserved.
Paid for by Onwordi Nkemdi Patrick.
