# Classical academic website starter

This is a static, multi-page academic homepage inspired by the **layout style** of https://lin.caltech.edu/index.html: blue title banner, understated navigation, narrow readable page, serif-free typography, and straightforward text-first sections. It does not copy the site's content or artwork.

## Files
- `index.html`: landing page, photo, biography, news and research interests
- `research.html`: two main research directions (scaling quantum information systems and probing fundamental physics), with project descriptions
- `publications.html`: paper list
- `notes.html`: notes and talks
- `cv.html`: short CV page
- `style.css`: shared colors, spacing, responsive layout
- `assets/profile-placeholder.svg`: replace with your own photo

## Personalize
1. Replace `Your Name`, email, university, office and advisor everywhere.
2. Place your photo in `assets/profile.jpg` and change the image path on `index.html`.
3. Edit the draft biography, research and publication entries. All text should be reviewed before publishing.
4. Add Scholar, GitHub and arXiv URLs; the bracketed references are **not live links**.
5. Place a PDF CV in this folder and link it from `cv.html` if desired.
6. Edit `--banner`, `--navy`, and `--content-width` in `style.css` to change the design.

## Preview
Open `index.html` in a browser. Navigation between pages works without a server.

## Publish with GitHub Pages
1. Create a public repository named `YOUR-USERNAME.github.io`.
2. Upload the **contents** of this folder (not the enclosing folder) to the repository root.
3. In your repository's **Settings → Pages**, set deployment to the main branch/root, if not enabled automatically.
4. Your site will appear at `https://YOUR-USERNAME.github.io/` after deployment.

No framework, npm, or build step required.

## Research copy
The Home and Research pages use the two research directions you specified. Check the wording about MITRE SiV work and the Eu:YSO symmetry measurement for exact project details before publishing; edit directly in `index.html` and `research.html`.
