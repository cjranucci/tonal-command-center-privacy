# Tonal Command Center — public privacy policy

This repository contains only the standalone public privacy-policy website. It is intentionally separate from the private application. Do not add application code, credentials, tokens, fitness records, databases, exports, or private configuration.

## Published policy

https://cjranucci.github.io/tonal-command-center-privacy/

GitHub Pages serves the root of the `main` branch, with HTTPS enforced. The site is plain HTML/CSS, has no JavaScript, analytics, or remote font dependencies, and needs no build or package installation.

## Update the policy

1. Edit `index.html` in this repository (GitHub’s web editor works), or edit it in a local clone.
2. Make sure descriptions match the application’s actual behavior. Before WHOOP collection is activated, update integration status and actual token/data storage handling.
3. Update the visible effective date and its `<time datetime>` value when changing the policy.
4. Commit to `main`. GitHub Pages republishes automatically.
5. Visit the public HTTPS URL without signing into GitHub and confirm the new text appears. Check Actions or Settings → Pages if deployment fails.

Optional local preview: run `python3 -m http.server 8090 --bind 127.0.0.1` in this directory and open http://127.0.0.1:8090/.

`styles.css` controls the mobile-friendly dark layout. `.nojekyll` tells Pages to serve these static files directly.
