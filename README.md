# portfolio2

This folder includes a GitHub Pages-ready static portfolio site.

No build step is required for the live site.
The publishable site is driven by these files:

- `index.html`
- `styles.css`
- `content.js`
- `script.js`
- `case-study-lp-refresh.html`
- `favicon.svg`
- `og-image.svg`
- `.nojekyll`

## Edit text and links

Most content lives in `content.js`.

Edit these fields first:

1. `site.name`
2. `site.email`
3. `hero`
4. `services.primary`
5. `work.items`
6. `contact.links`

The layout and styling live in `index.html` and `styles.css`.

## GitHub Pages deployment

If this folder is the root of your repository:

1. Push the files to GitHub.
2. Open the repository on GitHub.
3. Go to `Settings` -> `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select your main branch and `/ (root)`.
6. Save.

GitHub Pages will serve `index.html` directly.

## Notes

- The live site does not depend on Next.js.
- Existing older project files in this folder can be ignored if you are only publishing the static portfolio.
- `.nojekyll` is included so GitHub Pages serves the files without Jekyll processing.
