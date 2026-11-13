# Kovaro Aluminium – prototype

Single-page prototype of a "digital factory" website for a fictional aluminium manufacturer.

- `index.html` is the whole site: markup, styles and script in one file.
- 3D is drawn with three.js r128, loaded from cdnjs and jsDelivr. Fonts come from Google Fonts.
- No build step. Any static host serves it as is.

## Deploy on Vercel

Import this repository in Vercel and keep the defaults: framework preset "Other", no build command, output directory left empty.

## Notes

The company, numbers, certificates, systems and live data are examples made up for the prototype.

## Unlinked page

`swieta-2026/index.html` is a draft animated greeting card for KAMET S.A. It is not linked from the main page and carries a `noindex` tag; it is reachable only by its address, `/swieta-2026/`.
Drop the official logo next to it as `swieta-2026/logo.svg` and it replaces the text wordmark. A recipient's name can be added to the link as a plain hash, e.g. `/swieta-2026/#Anna-Kowalska`.
