# SEO NEO — Niche Edits Landing Page

Single-page ad landing for the "Supercharge Niche Edits with Cloud Stacked Backlinks" campaign. Static HTML, no build step, GitHub Pages ready.

## Live URL (after deploy)

`https://betchy1511-arch.github.io/seoneonicheedits/`

## Files

- `index.html` — self-contained landing page (HTML, CSS, JS, schema inline)
- `assets/` — reserved for logo, OG image, favicons (optional)
- `README.md` — this file

## Deploy to GitHub Pages

1. Clone or open the repo locally:
   ```bash
   git clone https://github.com/betchy1511-arch/seoneonicheedits.git
   ```
2. Copy `index.html` and `README.md` into the repo root.
3. Commit and push:
   ```bash
   git add .
   git commit -m "Add niche edits landing page"
   git push
   ```
4. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / root → Save**.
5. Wait ~1 minute. The page goes live at the URL above.

## Cross-page links (Also Supercharges block)

Each landing page includes an "Also Supercharges" block with 5 cards that link to the other niches. Matching repo names:

| Card | Target repo |
|---|---|
| Guest Posts | `seoneoguestposts` |
| PBNs | `seoneopbns` |
| Citations | `seoneocitations` |
| Press Releases | `seoneopressreleases` |
| Backlink Building | `seoneobacklinkbuilding` |

Create those repos and enable GitHub Pages on each for the cross-links to resolve. Until they exist, the links will 404, which is fine during rollout.

## Optional polish

- Drop a real `assets/logo.png` (~512px) to replace the inline SVG "Ne" mark in the nav and footer.
- Drop an `assets/og-image.png` (1200x630) for social share previews.
- Add a `CNAME` file if pointing a custom subdomain like `go.seoneo.io`.

## CTA

All primary CTAs link to `https://seoneo.io/` (main site signup). Change globally with a find-and-replace if you route ad traffic to a different signup URL.
