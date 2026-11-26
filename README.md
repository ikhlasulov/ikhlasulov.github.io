# ikhlasulov.github.io

Personal landing page for [@ikhlasulov](https://github.com/ikhlasulov): the
Linux apps Namaz and OpenRPM, plus smaller browser tools.

**Live site:** https://ikhlasulov.github.io/

## Structure

| English | Русский |
| --- | --- |
| `/` | `/ru/` |

Material 3 Expressive-inspired design with four accent palettes, automatic,
light and dark appearance, responsive navigation and reduced-motion support.
Content is plain HTML and works without JavaScript; the optional script only
controls appearance, ripples and finite reveal animations. Fonts are
self-hosted, and there is no tracking or analytics.

Each language has its own title, description, canonical address and language
alternates. `sitemap.xml` lists both pages.

## Editing

- Copy: `index.html` and `ru/index.html`. Both pages are maintained by hand;
  keep the two language versions in sync.
- Styles: `assets/style.css` (components, including a short adaptation block at
  the end) and `assets/tokens.css` (generated Material color roles; do not edit
  by hand).
- Script: `assets/site.js`.
- Images: `assets/avatar.jpg`, `assets/namaz-*.png`, `assets/openrpm-*.png`.

Preview locally:

```bash
python3 -m http.server 8765 --bind 127.0.0.1
```

The site is published by GitHub Pages from `main` / repository root, with
`.nojekyll`.

## Credits and license

The design is adapted from the GPL-3.0-only site
[Velmi1337/velmi1337.github.io](https://github.com/Velmi1337/velmi1337.github.io)
by Velmi1337, rewritten for these projects. See
[docs/design.md](docs/design.md) for the full list of sources and licenses.

The site code and copy are licensed under GPL-3.0-only, see `LICENSE`.
