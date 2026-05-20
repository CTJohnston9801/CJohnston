# Craig Johnston — Personal Website

A simple, fast, static personal site (plain HTML/CSS/JS — no build step).

## Files
- `index.html` — home page (About, Projects, Experience, Contact)
- `resume.html` — full styled résumé (printable / save-as-PDF in the browser)
- `styles.css` — warm & professional theme (shared)
- `resume.css` — résumé-page layout + print styles
- `script.js` — mobile menu, footer year, scroll-reveal
- `favicon.svg` — "CJ" monogram icon

The résumé was generated from a Word CV; that source `.docx` is kept local
(see `.gitignore`) and is not published.

## Editing
Open `index.html` and update the text directly. Look for the `<!-- ... -->`
comments — they mark the spots most worth personalizing (your bio, real
projects, job history, email, and LinkedIn URL).

## Preview locally
Just open `index.html` in a browser, or run a tiny local server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying
This site is published with GitHub Pages from the `main` branch.
Push changes to `main` and they go live automatically within a minute or two.
