# Cameron Afradi — plain one-page academic website

A classic academic homepage: **one `index.html`**, ordinary Arial, lists, links, and two small grayscale illustrations. No JavaScript, frameworks, hover artwork, or separate pages.

## Publish on GitHub Pages

1. Extract this ZIP.
2. Open https://github.com/cam-qis/cam-qis.github.io .
3. Upload/replace `index.html` and `style.css`; also upload the `assets` folder (keep filenames and paths intact).
4. Commit changes. Under Settings → Pages, publish from `main` and `/ (root)` if not already enabled.
5. Visit https://cam-qis.github.io . It may take a few minutes to update; hard-refresh after deployment.

Old `research.html`, `publications.html`, and other pages are no longer used. You can delete them from the repository once satisfied with the single-page version.

## Personalize

- For your headshot: upload `assets/profile.jpg`, and in `index.html` change `assets/portrait-placeholder.svg` to `assets/profile.jpg`. Use a roughly 4:5 image to keep cropping predictable.
- Edit the Ph.D. affiliation, research group, and email in `index.html` as needed.
- Replace text placeholders `[CV PDF]`, `[Google Scholar]`, `[ORCID]` with working links. For example, upload `assets/cv.pdf` then use `<a href="assets/cv.pdf">CV (PDF)</a>`.
- Edit each ordinary heading, paragraph, or `<li>` in `index.html` to add projects or publications.

The small bear and tiger images are noninteractive decorative art (`assets/bear-engraving.png` and `assets/tiger-engraving.png`); they can be removed by deleting their `<img>` tags.
