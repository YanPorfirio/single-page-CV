# Single-page CV

https://roadmap.sh/projects/single-page-cv

A one-page résumé built with HTML and CSS. No build step and no dependencies — open the file in a browser.

**Project page:** https://yanporfirio.github.io/single-page-CV/  
**Repository:** https://github.com/YanPorfirio/single-page-CV

The layout covers name and role, contact details, skills, education, experience, and LinkedIn / GitHub links.

## Preview locally

Open `singlepagecv.html` in a browser (double-click or drag the file onto a tab).

Or serve the folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000/singlepagecv.html`.

## Publish the URL

GitHub Pages serves this repo from the `main` branch (root). In the GitHub repo: **Settings → Pages → Build and deployment**, set **Source** to **Deploy from a branch**, branch **main**, folder **/ (root)**. The live URL is:

https://yanporfirio.github.io/single-page-CV/

`index.html` redirects to the CV so that root URL works.

## Structure

```text
single-page-CV/
├── index.html                 # redirect for GitHub Pages
├── singlepagecv.html          # résumé page (HTML + CSS)
├── image/
│   └── circle-user-solid-full.svg
└── README.md
```

## Customize

Edit `singlepagecv.html`:

- **Header:** name, role, and contact details
- **Skills, Education, Experience:** copy and the list of responsibilities
- **Across the web:** LinkedIn and GitHub URLs

Styles live in the `<style>` block in the same file (Outfit font, colors, and spacing).
