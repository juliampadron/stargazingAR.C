# stargazingAR.C
# Stargazing AR

Point your phone at the sky and see what's up there — Pokémon GO-style AR for stars, planets, and constellations.

## What it does

- Live camera view with labels for the brightest stars, planets, the Moon, and constellation outlines
- Labels are calculated on-device from your location, time, compass, and tilt
- Start screen with tonight's highlights
- Tap a star or planet for a detail card
- "Visible now" list with turn / tilt directions
- Toggles for stars, planets, and constellations
- Manual aim and sky-only mode
- Too-dark warning with a live Light badge, one-tap exposure boost, and a switch to sky-only mode

## How to use

1. Open the app on your phone in a modern mobile browser.
2. Allow camera, location, and motion / orientation access.
3. Point your phone at the sky — the labels follow where you're pointing.
4. Tap a label to see details about that star or planet.
5. Use Hide controls to get a clear view, and the Show controls pill to bring them back.

## Requirements

- A phone with a camera, compass, and motion sensors
- HTTPS — camera, location, and motion access require a secure connection
- A dark sky works best

## Running it

This is a single-file web app (`index.html`).

To run it on GitHub Pages: upload the files to your repository, then enable Pages from the main branch / root in Settings > Pages.

## Status

Beta. The compass is sky-guide accurate, not telescope accurate — labels will get you to the right star or planet, but not to arc-minute precision.

## License

MIT — see `LICENSE`.