# Summer CAMP — website

Save-the-date / announcement site for **Summer CAMP**, the Summer Conference on
Atomic and Molecular Physics — an inaugural, fully on-site AMO physics meeting,
**June 13–18, 2027** at the Chaminade Resort, Santa Cruz, California.

## Structure
- `index.html` — the entire site (self-contained: HTML + CSS + a little JS; Google Fonts via CDN).
- `assets/logos/` — sponsor logo slots (`moore.svg`, `heising-simons.svg`, `ciqc.svg`).
  These are placeholder wordmarks; replace each file with the real logo, keeping the filename.

## Editing
Open `index.html` in a browser to preview, or run a local server from this folder:

```sh
python3 -m http.server
# then open http://localhost:8000
```

All colors, type, and spacing are CSS custom properties at the top of `index.html`
(`:root { ... }`). The nav includes **Program** and **Register** "coming soon" stubs with
`EXTEND-HERE` comments showing where the full program and registration (with online
payment) will slot in later.

## Hosting
Published with GitHub Pages from the `main` branch (root). To attach a custom domain,
add a `CNAME` file and set the domain in the repository's Pages settings.
