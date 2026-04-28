# PMAX Real Estate · 2026 Strategic Briefing

A live briefing site for PMAX BrandCom Board of Management — consolidating the four working documents of the Real Estate vertical into one shareable web page.

**Live site:** _will be available at_ `https://<your-username>.github.io/PMAX-RealEstate-2026-Briefing/`

---

## What's inside

The site has four parts, each with a topline recap and a CTA to the full document:

1. **PMAX Real Estate Strategic Brief V2** — capability status, 2026 market context (5 fault-lines), 4 strategic moves.
2. **PMAX Capability Deck** — 3 flagship products, data + tech moat, hero cases.
3. **H2 2026 Roadmap V2** — 3 priority products + 2 GTM campaigns + Challenger Forum (Q4 flagship). _The decisions for BOM live here._
4. **Vietnam Real Estate Market Research** — the data underneath, in topline form.

## How to deploy on GitHub Pages

1. Create a new GitHub repository (suggested name: `PMAX-RealEstate-2026-Briefing`).
2. Upload `index.html` and `README.md` to the repo root.
3. In repo Settings → Pages → Source: select `main` branch, `/` (root) folder.
4. Save. GitHub Pages will publish at `https://<username>.github.io/PMAX-RealEstate-2026-Briefing/` within ~1 minute.
5. Share the URL with BOM.

## Tech notes

- Single HTML file. Self-contained. No build step.
- Google Fonts (Inter + Playfair Display) loaded via CDN.
- Responsive (mobile + tablet + desktop).
- PMAX brand colours throughout (red `#E11D2A`, navy `#1A1A2E`).

## Updating content

Edit `index.html` directly. The four sections are clearly demarcated with `<!-- ============= PART N ============= -->` comments. Each part is a self-contained `<article class="part-card">`.

To update a CTA link, find the `href` inside the `cta-button` `<a>` tag in the relevant part.

---

_Prepared by PMAX BrandCom Strategy · Q2 2026_
