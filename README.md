# fagdag-redirect

Static GitHub Pages site that redirects `fagdag.entur.org` to
[fagdag.entur.no](https://fagdag.entur.no), preserving path, query and hash.

- `index.html` handles the root.
- `404.html` handles all other paths (GitHub Pages serves it for unknown URLs).
- DNS: `fagdag.entur.org` CNAME → `entur.github.io`, custom domain set in Settings → Pages.

The actual site lives in [entur/knutepunkt](https://github.com/entur/knutepunkt).