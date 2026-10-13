# website_dev

A small collection of standalone HTML/CSS design experiments for my personal website (max-z.de), kept separate from the main production site.

## Live previews

- **CV card:** https://maxizu.github.io/website_dev/cv/cv.html
- **DEV placeholder:** https://maxizu.github.io/website_dev/dev/index.html

## Contents

```
cv/
  cv.html     Business-card style contact card with hover "bracket" animation
  cv.css      Styling (self-hosted JetBrains Mono font via jsDelivr CDN)

dev/
  index.html  Minimal "under construction" placeholder page
  style.css   Styling + corner-loader animation
```

### `cv/` – Contact card

A flipped-business-card-style layout with six linked fields (Job, Me, Instagram, Loc, Mail, Git), each framed by animated corner brackets that change color on hover. Links point to sections on the main site (`max-z.de/#resume`, `max-z.de/#contact`) and external profiles.

### `dev/` – Placeholder page

A simple dark "DEV" splash screen with four animated corner-loader bars, intended as a temporary placeholder (e.g. during maintenance or while a new design is in progress).

## Notes

- No build step, no dependencies beyond the Google/jsDelivr-hosted font in `cv.css`.
- These pages are independent one-offs, not part of the main site's codebase or deployment.
