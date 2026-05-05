# 233 Starr Karaoke & Eats — Concept by Family Studio WE2

A design concept and live website prototype for **233 Starr Karaoke & Eats** (233 Starr St, Brooklyn, NY 11237), prepared by **Family Studio WE2**.

---

## What's in this repository

| File | URL path | Purpose |
|---|---|---|
| `guide.html` | `/guide.html` | Bilingual EN/RU walkthrough explaining every feature in the concept (this is the page you share with the client first) |
| `index.html` | `/` | The actual live concept website — a fully working multi-page SPA with custom interactions |
| `screenshots/` | — | Device-frame screenshots used in `guide.html` |
| `team/` | — | Photos of the WE2 team |

The two pages cross-link with two fixed buttons:
- On `guide.html` — a single bottom-center pill **"Open Live Site"** opens `index.html` in a new tab
- On `index.html` — a top-center pill **"Back to Guide"** appears only when the visitor arrives from `guide.html` (via `?from=guide` URL param or matching referrer)

---

## How to publish on GitHub Pages

1. Create a new public repository on GitHub
2. Drop the entire contents of this folder into the root of that repo
3. Push to the `main` branch
4. Open repo Settings → Pages → set Source = `Deploy from a branch`, Branch = `main`, Folder = `/ (root)`
5. Save. After a minute the site will be live at `https://<your-username>.github.io/<repo-name>/guide.html`

The client should land on the **guide first** — share the URL ending in `/guide.html`, not the bare domain.

---

## Concept highlights (full breakdown in `guide.html`)

1. **Mobile-first hero** — gold "233 STARR" wordmark, info pills, two CTAs above the fold
2. **"Play the Vibe"** — synthesised club beat + full-screen light show, opt-in only
3. **Daily Specials + Happy Hour** — built-in repeat-visit engine
4. **Starr Packs** — three flagship party packages with "Most Popular" anchor
5. **Full Eats & Drinks menu (desktop)** — categorised, filterable
6. **Menu (mobile)** — single-column with horizontal-scroll category strip
7. **Reservation flow** — progressive disclosure across 7 steps + custom success modal
8. **Sticky mobile bar** — Call · Reserve · Instagram, plus 4.9★ / 279 Google reviews
9. **Star cursor (desktop)** — gold SVG five-point star matching the brand mark

---

## Tech notes

- Two static HTML files, zero build step. Works as plain GitHub Pages output.
- Vanilla JS, vanilla CSS. No framework dependencies.
- Audio is generated live via Web Audio API — no MP3 file required.
- Map embed via OpenStreetMap iframe (no API key required).
- Dark/Light + EN/RU toggles live in `guide.html`.

---

## Copyright

Design, code and creative work are © Family Studio WE2 and protected under U.S. copyright law (17 U.S.C. § 102) until rights transfer to the client. Detailed legal block is included at the bottom of `index.html`. Photography of 233 Starr's venue, food, drinks, signage and brand identity remain the property of 233 Starr Karaoke & Eats. Stock photography in the menu sections is licensed for demo use only and will be replaced with the client's own production photography upon commission.
