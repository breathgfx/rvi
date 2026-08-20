# RVI Centre — Website Design

**Live preview: [breathgfx.github.io/rvi](https://breathgfx.github.io/rvi/)**

A template-family website design for the RVI Centre, built as a [Claude Design](https://claude.ai) canvas: a shared component set (nav, cards, tags, footer) applied across a unique Home page and a shared section-landing / detail template pair, in desktop and mobile.

## Pages

- [`Home.dc.html`](Home.dc.html) — Home page
- [`Publications.dc.html`](Publications.dc.html) — Section-landing template (shown as Publications)
- [`Publication Detail.dc.html`](Publication%20Detail.dc.html) — Detail template
- [`RVI Website.dc.html`](RVI%20Website.dc.html) — Canvas index / overview
- [`RVI Website-print.dc.html`](RVI%20Website-print.dc.html) — Print-friendly layout
- [`RVI Centre Design Preview.html`](RVI%20Centre%20Design%20Preview.html) — Standalone, self-contained preview build

## Design system

The `_ds/` directory holds the **Modernist** design system these pages are built on: a flat, architectural style set in Archivo, with a near-mono red-on-white palette, a visible modular grid, zero corner radius and strong 2px rules. See [`_ds/modernist-afa70314-ff96-4da1-bdc0-0ca18583e92d/readme.md`](_ds/modernist-afa70314-ff96-4da1-bdc0-0ca18583e92d/readme.md) for the full token and component reference (colors, type, spacing, components).

## Supporting files

- `rvi.css` — page-level styles
- `support.js`, `doc-page.js`, `image-slot.js` — canvas runtime/support scripts used by the `.dc.html` pages

## Viewing

Open any `.dc.html` file or `RVI Centre Design Preview.html` directly in a browser.
