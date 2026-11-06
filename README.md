# Badass On Demand · Fri, Nov 20

**Start here, Mark.** Everything for the Nov 20 launch lives in this repo: the event page, the marketing plan, the launch kit and the research behind them.

**Live event page:** https://badass-on-demand-event.onrender.com

## What's in here

| Path | What it is |
| --- | --- |
| `index.html` | The event page. Every change pushed to `main` goes live in about a minute. |
| `assets/img/` | Background photography. Every image shows the reader's world, never us. |
| [`docs/nov-20-launch-kit.md`](docs/nov-20-launch-kit.md) | **Use this week.** 14-day plan, Office Hours → Nov 20 flow, promo copy for referrers, tracking, seat math. |
| [`docs/marketing-plan.md`](docs/marketing-plan.md) | Positioning, buyers, offer ladder, Office Hours engine, channel plays, 90-day roadmap, metrics, owners, risks. |
| [`docs/research.md`](docs/research.md) | badassondemand.com audit, public footprint, your own playbook in your words, competitors, benchmarks. |
| `render.yaml`, `robots.txt` | Hosting config. The page is hidden from search engines until launch. |

## What the page does

- Sells **Badass On Demand on Fri, Nov 20** to senior leaders, owners and founders. The reader is the hero; you're the guide.
- Introduces free **Open Office Hours** (Tue, Nov 17, then every other Tuesday) as the warm-up for anyone not ready to commit. After Nov 20 the page switches itself to Office Hours only.
- **Leadership Scale Assessment:** 15 statements, scored live, with the two gaps costing the reader most.
- **Leadership Drag Calculator:** what turnover, the leader's time and team drag cost a year, in dollars.
- Tabs for owners and founders, franchise systems, family offices, incubators and accelerators, and conference companies, plus an Event MC & Host section.
- Links back to bigimpacthq.com and your LinkedIn.

## What we need from you

- [ ] Nov 20: time, location, price and seat cap (shown as TBC on the page)
- [ ] Office Hours: day, time, seat cap, and OK on the attendee bonus (first pick of the live hot seats)
- [ ] One revenue figure for bios: the site says $150M+, a 2021 bio says $51M+
- [ ] 3 testimonials from senior leaders (ideally a founder, a franchisor, a family office)
- [ ] A headshot, the host reel link, the Zoom details and a booking link for B2B briefings
- [ ] Domain: point badassondemand.com here, or keep Kartra and link across

## Before launch

- Remove the `noindex` tag and `robots.txt`.
- Connect both forms to Kartra (tag by audience; keep the "Who invited you?" field).
- Link this page from bigimpacthq.com and your LinkedIn Featured section.
- Review the assessment statements, scoring bands and advice.

## Making changes

Edit `index.html` on GitHub and commit to `main`; Render redeploys automatically. To preview locally:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080.
