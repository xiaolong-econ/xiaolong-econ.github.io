# Xiaolong Hou — Academic website

A simple academic website inspired by al-folio’s restrained typography and spacing. Built with plain HTML and CSS, with no installation or build step required.

Website: https://xiaolong-econ.github.io/

## Update the website

Edit a file on GitHub and commit the change to `main`:

- `index.html`: biography, affiliation, and contact information.
- `research.html`: publications, working papers, and work in progress.
- `teaching.html`: courses, evaluations, and awards.
- `cv.html`: education and link to the full CV.
- `style.css`: layout, colors, and typography.

The CV and course evaluations link to the existing Google Drive documents. Site content was migrated from https://sites.google.com/view/xiaolong-hou/home.

## Publish

In Settings → Pages, select **Deploy from a branch**, **main**, and **/(root)**. Changes to `main` then publish automatically. `.nojekyll` keeps the site as plain static files.

## Local preview

From the repository folder, run `python3 -m http.server 8000`, then open http://localhost:8000.
