# Yitz Jordan — research and engineering

Published at https://ylove.github.io/ using GitHub Pages from `main`, repository root.

- `index.html`: portfolio and research homepage.
- `assets/home.css`: responsive styling and CSS-only hero animations, with reduced-motion support.
- `llms-freestyling/index.html`: the original article at its permanent `/llms-freestyling/` URL. Article content and styling are preserved.
- `robots.txt` and `sitemap.xml`: discovery of the homepage and article.
- `.nojekyll`: direct static publishing with no build dependencies.

Edit, commit, and push to `main` to publish. Use root-level article directories for stable extensionless URLs; update the homepage and sitemap when adding an article.

Both pages use a restrictive Content Security Policy: no JavaScript, forms, frames, or external resources. The article authorizes its embedded stylesheet by SHA-256 hash. If you change that stylesheet, update its CSP hash using the exact UTF-8 text between `<style>` and `</style>` (including surrounding newlines). The homepage permits same-origin CSS.

## Publishing security

GitHub repository permissions control publishing; public visitors cannot edit the deployed site. Keep repository access limited to `ylove`, publish only `main`, and do not grant write deploy keys or unreviewed app access. Use account 2FA/passkeys and review authorized tokens and GitHub Apps regularly. Branch rules and browser policies cannot protect against compromise of the owner account.

This repository is public. Keep credentials, private datasets, unpublished drafts, and personal information elsewhere. Deleting a file does not remove it from Git history. No open-source or Creative Commons license is granted by this repository.
