# 🌵 Coachella 2026 Weekend 2 — Interactive Schedule Planner

**[→ Open the Planner](https://devonance.github.io/coachella-schedule/)**

An interactive schedule planner for Coachella 2026 Weekend 2 (April 17–19). Browse ~175 performers across all 9 stages, build a personal plan, detect schedule conflicts, and export your plan as a PNG.

![Coachella 2026](https://img.shields.io/badge/Coachella-2026-E07A5F?style=flat-square) ![Weekend 2](https://img.shields.io/badge/Weekend_2-Apr_17--19-3D405B?style=flat-square) ![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-222?style=flat-square)

## Features

- **Full Schedule Grid** — Every performer across Coachella Stage, Outdoor Theatre, Mojave, Sahara, Gobi, Sonora, Yuma, Quasar, and Do LaB
- **Genre Filters** — Toggle Pop, Hip-Hop, Electronic, Rock/Punk, Indie, R&B, Latin, K-Pop, Jazz, D&B/Bass
- **Artist Detail Cards** — Set times, stage, genre, Spotify link, and setlists from Weekend 1 (Sabrina Carpenter, Justin Bieber, KAROL G)
- **Personal Planner** — Add/remove artists, see walking times between stages
- **Conflict Detection** — Flags time overlaps AND insufficient walking gaps between stages
- **Timeline Scrubber** — Drag to see who's playing at any moment with live "Now Playing" badges
- **Interactive Map** — SVG stage map with real-time performer indicators
- **Shuttle Schedule** — Official shuttle arrival/departure times
- **Export to PNG** — Download your personal plan as an image
- **Day Tabs** — Switch between Friday, Saturday, and Sunday independently

## Data Sources

- Set times from the [official Coachella schedule](https://www.coachella.com/schedule) (confirmed identical for both weekends)
- Setlists from Weekend 1 performances via [setlist.fm](https://www.setlist.fm/festival/2026/coachella-festival-2026-53d52f4d.html), [Capital FM](https://www.capitalfm.com/), [Just Jared](https://www.justjared.com/)
- Spotify artist links confirmed via Spotify Web API
- Shuttle information from [Valley Music Travel](https://coachella.valleymusictravel.com/shuttles) and [EDM Identity](https://edmidentity.com/)
- Walking times between stages from multiple festival guides

## Tech Stack

Single `index.html` file — no build system required:
- React 18 (CDN)
- Babel Standalone (for JSX compilation)
- Vanilla CSS (no Tailwind, no frameworks)
- Canvas API for PNG export

## Deployment

This is a single HTML file. Just push to GitHub and enable Pages:

1. Go to repo Settings → Pages
2. Set source to "Deploy from a branch"
3. Select `main` branch, `/ (root)` folder
4. Save — site will be live at `https://devonance.github.io/coachella-schedule/`

## Notes

- **Anyma's Weekend 1 Friday midnight set was canceled** due to high winds. Weekend 2 status TBD — check [@coachella](https://twitter.com/coachella)
- Weekend 2 has a **different Do LaB lineup** than Weekend 1 (SBTRKT, Seth Troxler, A-Trak, Tourist, etc.)
- **Big Boi** replaces Sean Paul at Heineken House for Weekend 2
- Lambrini Girls and Solomun are **not performing** at Coachella 2026

## License

This is a fan project. Coachella® is a registered trademark of Goldenvoice / AEG Presents. All artist names and likenesses belong to their respective owners.
