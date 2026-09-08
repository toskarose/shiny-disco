# TOSKAROSE Folio — V1

A first working build of the dark-forest interactive folio.

## Included
- Dark forest visual environment using the supplied photographs
- Moth visual
- Custom cursor
- TOSKAROSE landing page
- Music archive sorted newest → oldest:
  - 2025: Cozy Diaries Chapter 1, Chapter 2
  - 2024: Saddle Up, Obsessed, Breakin Down Ur Door
  - 2023: Alice in Wonderland, Special, Delulu
- Click a track to reveal its title/year and play the supplied audio
- Responsive mobile layout

## Run locally
Open `index.html` in a modern browser.

For the most reliable audio behavior, run a tiny local server from this folder:

`python3 -m http.server 8000`

Then visit `http://localhost:8000`.

## Next pass
1. Replace the placeholder contact email.
2. Adobe Font `bd-terminal-vf` is now loaded from the supplied Typekit stylesheet and used for the final contact heading.
3. Add the rest of the folio sections/content.
4. Refine the moth interaction and photo transitions.
5. Add your final custom cursor asset.
