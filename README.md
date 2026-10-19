# SELENE — Watch the Earth rise

A one-page concept site for a fictional lunar expedition company. Scroll to clear the dust,
watch the Earth rise over the Moon, follow the flight path, browse the mission log and join the waitlist.

Created by Mariyam Babar. Names, dates and missions are illustrative placeholders.

## Files

```
index.html      the whole site (HTML + CSS + JavaScript)
images/         hero layers (sky, earth, moonscape, frame, astronaut, ground) and mission-log photos
.nojekyll       tells GitHub Pages to serve the files as-is
```

No build step, no npm, no dependencies. Fonts (Michroma, Manrope, IBM Plex Mono) load from Google Fonts.

## Run locally

Open `index.html` in a browser. Keep the `images/` folder next to it.

## Publish on GitHub Pages (free)

1. Push everything in this folder to a GitHub repository (files at the repo root).
2. Repository → **Settings → Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch **main**, folder **/ (root)**, then Save.
4. After a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Publish on Vercel (optional)

Import the repository at vercel.com → Framework Preset **Other**, leave build command and output directory empty, Deploy.

## Change the content

- Text: search `index.html` for the section you want (`LOG`, `LEGS`, `MIS` near the bottom `<script>`).
- Email for the waitlist form: search for `crew@selene.space`.
- Launch-window countdown date: search for `2031-07-20`.
