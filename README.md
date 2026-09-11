# Qasem Alolaywi — Portfolio

Personal portfolio site. A single self-contained `index.html` — no framework, no build step, no dependencies.

## Run it

Open `index.html` in a browser, or serve it locally:

```bash
python3 -m http.server 4000
# then open http://localhost:4000
```

## Structure

```
index.html    # the entire site: markup, styles and theme toggle
```

## Editing

**Replace the photo.** The hero image is `photo.jpg` (640x640, cropped square).
Swap the file, keeping the same name and a square aspect ratio.

**Add a certification.** Copy any `.mini` block in the Education & Certifications
section and edit the title and meta line.

**Change colours.** Every colour is a CSS custom property defined at the top of the
`<style>` block — edit `--accent` and the rest follows. Light and dark palettes are
defined separately; the toggle in the nav persists the choice to `localStorage`.

## Publishing

Live at **https://qasem-o.github.io/portfolio/** via GitHub Pages (deploys from `main` / root).
Every push to `main` goes live within a minute or two.

The site is plain static files, so it also works on Netlify, Vercel or any other static host.
