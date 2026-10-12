# BAPI Sample Website

A sample redesign **concept** for the Bangladesh Association of Pharmaceutical Industries (BAPI) home page.

> **N.B.** This is **not** the official BAPI website and is not affiliated with or endorsed by BAPI. It is a design concept only.

Live version: <https://saizul.com/bapi-sample-website/>

## What is inside

A single static page (`index.html`) with the site header, home page content and footer:

- Fixed notice bar and navigation (mobile menu included)
- Hero section with animated headline
- Full-page Three.js background: floating pill capsules that morph into a rotating export globe while scrolling
- Animated counters, About timeline, Competitive Edge cards, API Park panel, News cards, marquee and CTA

No build step is needed.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

then visit <http://localhost:8000>.

## Libraries (loaded from CDN)

- [Three.js](https://threejs.org/) r128
- [GSAP](https://gsap.com/) 3.12.5 + ScrollTrigger
- Google Fonts: Space Grotesk, Inter

## Notes

- The navigation links to the other pages (About Us, Pharma Industry, Leadership, Members Directory, Contact) point to the live sample site on saizul.com.
- Photos are public-domain images from Wikimedia Commons (NIH / NHGRI), loaded directly from Wikimedia.
- The BAPI logo is loaded from the live sample site and falls back to a small Bangladesh flag mark if unavailable.

## Credit

Design and developed by [Saizul Amin](https://saizul.com/).
