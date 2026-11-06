# Badass On Demand · Event page (concept draft)

Single-page event site for **Badass On Demand**, a live event on **Fri, Nov 20, 2026** for senior leaders, owners and founders. Free **Open Office Hours** (Tue, Nov 17, then every other Tuesday) is the warm-up that feeds it.

This is a **review draft**: a banner on every view says so, forms do not submit, and the page is set to `noindex`.

## What's on the page

- Event hero and registration (Nov 20) with the "It's go time" qualifier list
- Leadership Scale Assessment (15 statements, scored live in the browser)
- Leadership Drag Calculator (turnover, leader time, team drag)
- Audience tabs: owners and founders, franchise systems, family offices, incubators and accelerators, conference companies
- Event MC and Host section
- Client results (verbatim excerpts from bigimpacthq.com)
- Open Office Hours as the warm-up; after Nov 20 the page switches itself to Office Hours only

## Preview locally

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080.

## Deploy

- **Render:** New, then Blueprint, then pick this repo. `render.yaml` serves the repo root as a static site.
- **GitHub Pages:** Settings, then Pages, then deploy from the `main` branch, root folder.

## Before launch

- Confirm Nov 20 time, location, price and seat cap (shown as TBC)
- Confirm the Office Hours day, time and cap, and the proposed attendee bonus
- Replace the review banner, remove `noindex` and `robots.txt`, and wire the forms to Kartra
- Add 3 testimonials from senior leaders, a headshot and the host reel link
