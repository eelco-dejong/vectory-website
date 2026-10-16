# vectorydigital.nl — the Vectory website

The public website of Vectory (Vectory Digital, a trade name of EDJ Holding B.V.). Two static pages, no build step,
no cookies, no third-party requests. Published by GitHub Pages from the root of `main`.

| File | What it is |
| --- | --- |
| `index.html` | The homepage (one page with anchors: service, platform, responsibilities, pricing, contact) |
| `privacy.html` | The privacy policy |
| `assets/` | Logos (SVG), portrait, favicon, Open Graph image, and the Arimo font (SIL OFL, self-hosted) |
| `CNAME` | The custom domain for GitHub Pages: `vectorydigital.nl` |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## How a change is made

1. Eelco asks for the change in the Business Analyst chat.
2. The BA changes the design on the canvas *Vectory website* and hands over the new HTML.
3. Claude Code replaces the files here, commits and pushes to `main`. GitHub Pages publishes within a few minutes.

Rules: keep the site free of cookies, trackers and externally loaded files (the privacy policy says so); keep the
colours and type of the Vectory brand guidelines v0.1; text in English.
