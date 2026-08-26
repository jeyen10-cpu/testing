# 10 Days in Japan — A Planning Guide from Malaysia

A single-page, self-contained article covering a 10-day Tokyo → Hakone → Kyoto → Nara → Osaka itinerary, written for travellers flying out of Kuala Lumpur. Includes a day-by-day route timeline, city comparison table, JR Pass vs. IC card comparison, a budget breakdown, and packing tips.

Live view: open `index.html` directly, or publish with GitHub Pages (instructions below).

## Files

| File | Purpose |
|---|---|
| `index.html` | The full article — HTML, CSS, and inline SVG charts in one file. No build step, no dependencies to install. |
| `README.md` | This file. |
| `LICENSE` | MIT license for the page's code (markup/CSS). Photo credits are separate — see below. |

## Publishing with GitHub Pages

1. Create a new repository on GitHub and upload these files to the root (or `git push` them — see below).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save. GitHub will publish the page at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

### Pushing from the command line

```bash
git init
git add index.html README.md LICENSE
git commit -m "Add 10-day Japan itinerary guide"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

## Notes

- The page uses Google Fonts (Shippori Mincho, Noto Sans, Space Mono) loaded via `<link>` tags — an internet connection is needed for the fonts and photos to load; everything else (layout, charts, tables) is self-contained in `index.html`.
- Photos are hotlinked from Wikimedia Commons via their `Special:FilePath` redirect and are licensed under Creative Commons (CC BY / CC BY-SA) or public domain, with individual credit lines shown under each image in the article. If you'd rather not depend on Wikimedia's servers, download the photos and swap the `<img src>` values for local paths (e.g. `images/senso-ji.jpg`).
- All budget figures (RM/¥) and JR Pass prices reflect 2026 research at time of writing and should be re-checked before travel, since fares and pass pricing change.
