# Crosslake Cabin website

Static site for the Crosslake cabin (Big Trout Lake, Crosslake, MN). Plain HTML and CSS, no build step, served by GitHub Pages from `main`. Push to `main` and it's live in about a minute.

- `index.html`: all page content, plus structured data (VacationRental and FAQPage JSON-LD) in the head.
- `styles.css`: palette and layout.
- `img/`: photos (webp) and the link-preview image.
- `robots.txt`, `sitemap.xml`, `llms.txt`: search and AI-crawler basics.

Live at https://crosslakecabin.com (custom domain via the `CNAME` file; DNS at GoDaddy: four A records for @ to GitHub Pages, CNAME www to cirriuspersonal.github.io).

Facts on the page come from the STR Ops Vault (COP - Ops, Hospitable settings). Change the page when those change: check-in 12:00 PM, check-out 10:00 AM, two-night minimum.
