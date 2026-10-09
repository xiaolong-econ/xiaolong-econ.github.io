# Xiaolong Hou — Academic website

A simple academic website inspired by al-folio’s restrained typography and spacing. Built with plain HTML and CSS, with no installation or build step required.

Website: https://xiaolong-econ.github.io/

## Update the website

Edit a file on GitHub and commit the change to `main`:

- `index.html`: biography, affiliation, portrait, and contact information.
- `research.html`: publications, working papers, and work in progress.
- `teaching.html`: courses, evaluations, and awards.
- `cv.html`: education and link to the full CV.
- `style.css`: layout, colors, and typography.
- `photo.jpeg`: professional portrait.
- `CV.pdf`: full CV; replace this file to update the downloadable CV.

The CV and portrait are hosted directly in this repository. Course evaluations link to the existing Google Drive documents. Site content was migrated from https://sites.google.com/view/xiaolong-hou/home.

Publications are grouped under **Economics** and **Public Policy & Health**. Keep published author order and bold Xiaolong Hou's name. A short parenthesized note appears beside each group heading and wraps below when space is limited. At Xiaolong Hou's request on 9 October 2026, Economics displays **(All authors contributed equally)** without authorship symbols. In Public Policy & Health, **#** marks first author and **\*** marks corresponding author. Xiaolong Hou confirmed on 9 October 2026 that he is corresponding author on the PrEP paper (2026) and first author only on the medical-training paper (2025). For future papers, confirm roles from the publication or author before adding markers.

## Publish

In Settings → Pages, select **Deploy from a branch**, **main**, and **/(root)**. Changes to `main` then publish automatically. `.nojekyll` keeps the site as plain static files.

## Local preview

From the repository folder, run `python3 -m http.server 8000`, then open http://localhost:8000.
