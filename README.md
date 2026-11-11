# Deathventory: Ember Road — Player Field Kit & Support Site

Static player information, support/controls guide, and privacy-policy pages for **Deathventory: Ember Road**, styled directly from the game’s `ThemePalette`, `UiStyle` stitched-leather chrome, and CC0 `Ember Road` pixel font.

Hosted with GitHub Pages from the root of `main`:

- Home: https://growlite.github.io/deathventory-support/
- Support: https://growlite.github.io/deathventory-support/support/
- Privacy: https://growlite.github.io/deathventory-support/privacy/

## Included Visual Assets (`assets/`)

- `ember-road.woff` / `ember-road.ttf` — Generated deterministically from the game’s CC0-1.0 `Ember Road` 5×7 pixel glyph tables (`font_glyphs.py` + `spanish_glyphs.py`, covering ASCII + Spanish accented characters and symbols).
- `title-logo.png`, `hero-road.jpg`, `app-icon.png`, `favicon.png` — First-party game logo, menu road illustration, and backpack app icon owned by the project.
- Buildless static HTML + CSS (`styles.css`), with `.nojekyll`, zero JavaScript, zero analytics, and zero third-party font/CDN requests.

## Pre-Release Checklist

These pages keep `<meta name="robots" content="noindex,nofollow">` and explicit provisional notices where final publisher details are still pending. Before App Store submission:

1. Replace the privacy placeholder notice in `privacy/index.html` with the reviewed final privacy policy and privacy contact address.
2. Add the approved public support contact address to `support/index.html`.
3. Confirm final English and Spanish copy against the qualified release candidate.
4. Remove `noindex,nofollow` when ready for search discovery.
