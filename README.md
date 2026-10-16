# CTFI Website

Static website for the Center for Therapeutics in Fibrosis and IBD.
Plain HTML and CSS. No build step and no dependencies.

## What to upload to GitHub (and nothing else)
- `index.html`, `approach.html`, `research.html`, `resources.html`,
  `people.html`, `gallery.html`, `contact.html`: the pages
- `styles.css`: the shared stylesheet
- `.nojekyll`: tells GitHub Pages to serve every file as-is
  (hidden on Windows unless "Hidden items" is on in File Explorer)
- `README.md`: this file
- `Pictures/`: the 31 `.jpg` images the pages use. Any other file in
  Pictures (original covers, PDFs, GIFs, names with spaces) is not used by
  the site and should not be uploaded.

## Deploy with GitHub Pages
1. Create a new repository on GitHub (e.g. `ctfi-website`), Public.
2. Upload the files above to the repository root, so that `index.html`
   sits at the top level and the images are in a `Pictures` folder.
3. In the repository: Settings, then Pages. Source: Deploy from a branch.
   Branch: main. Folder: / (root). Save.
4. After about a minute the site is at `https://<username>.github.io/<repo-name>/`.
