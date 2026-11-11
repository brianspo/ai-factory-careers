# AI Factory Careers page

Static site, three files, no build step.

- `index.html` page (CSS inline, Google Fonts for Source Sans 3 and Oswald)
- `og-image.png` 1200x630 link-preview card
- `cal-poly-logo-white.png` header logo

## Before publishing
1. Confirm the final URL. `index.html` assumes `https://ai.calpoly.edu/` in `canonical`, `og:url`, `og:image` and `twitter:image`. Find/replace if different (LinkedIn needs absolute image URLs).
2. Abolition is Cal Poly's licensed brand font and is listed first in the headline stack. If the host serves it (ai.calpoly.edu on the WordPress theme would), it is used; otherwise Oswald is the fallback.
3. After deploying, run the URL through https://www.linkedin.com/post-inspector/ to refresh the cached card.

## Hosting options
- calpoly.edu: hand the folder to web/ITS, or upload as-is to any static path.
- GitHub Pages: push the folder, Settings > Pages > deploy from branch. Update the URLs in step 1 to the github.io address.
- Netlify Drop: drag the folder onto app.netlify.com/drop. Update URLs to the netlify.app address.
