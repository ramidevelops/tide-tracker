# Tide Tracker

Static site. No build step, no server. Works on GitHub Pages.

## Deploy
1. New GitHub repo (e.g. `tide`).
2. Upload everything in this folder to the repo root: `index.html`, `app.js`, `styles.css`, `fonts/`.
3. Settings > Pages > Deploy from a branch > `main` / root.
4. Open `https://<you>.github.io/tide/` on your phone.

## Compass
- Tap **Use compass**. iPhone asks for Motion & Orientation access once per visit.
- Needs HTTPS (GitHub Pages is). Hold the phone portrait, flat or upright.
- Compass is magnetic; the page subtracts 5 degrees (Tampa Bay declination) to match NOAA's true directions. The arrow's up = where your phone points.
- Add `?debug` to the address to show the phone heading in degrees true.

## Fonts
ABC Areal (variable) is in `fonts/`. Text uses its MONO axis at 0, numbers at 100. If this repo is public the font file is public too, so check your web license covers that.

## Data
Tide and current come from NOAA harmonic constants (St. Petersburg 8726520; current stations at Skyway, Egmont Channel, Port Manatee, Old Tampa Bay), computed on the phone. Predictions only, not a live gauge. Not for navigation.
