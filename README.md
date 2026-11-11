# Cal Poly AI Factory Careers

Recruiting page for three positions supporting Cal Poly's NVIDIA DGX B200 AI Factory. Static site, no build step.

Live: https://brianspo.github.io/ai-factory-careers/

## Files
- `index.html`: the page (CSS inline; Source Sans 3 and Oswald load from Google Fonts)
- `ai-factory-racks.jpg`: hero photo (1600 px wide)
- `og-image.png`: 1200x630 link-preview card for LinkedIn and X
- `cal-poly-logo-white.png`: header logo
- `.nojekyll`: tells GitHub Pages to serve files as-is

## What's on the page
Hero with photo, program overview with BasePOD diagram, three role sections (linkable at `#facilitator`, `#sysadmin`, `#engineer`), "Why Cal Poly", and an Apply section with direct links to the three postings on jobs.calpoly.edu. Light and dark themes follow the visitor's system setting.

Deliberately left out: salaries (the postings carry them), internal candidates, budget history and staffing plans.

## Editing
Change `index.html` and push to `main`; GitHub Pages redeploys in about a minute. Posting URLs are in the Apply section and at the end of each role section.

## Moving to calpoly.edu
1. Copy the folder to the new host.
2. In `index.html`, replace `https://brianspo.github.io/ai-factory-careers/` with the new URL in `canonical`, `og:url`, `og:image` and `twitter:image`. LinkedIn needs absolute image URLs.
3. If the host serves Abolition (Cal Poly's licensed headline font), the page uses it automatically. Otherwise it falls back to Oswald.
4. Re-run the URL through https://www.linkedin.com/post-inspector/ so LinkedIn refreshes its cached card.

## After editing the hero photo or headline
Regenerate `og-image.png` so the link card matches the page.
