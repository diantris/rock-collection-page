# Rock Collection

A public catalogue of a personal collection of rocks, minerals and cabochons, published with GitHub Pages at
**https://diantris.github.io/rock-collection-page/**.

Many of the specimens are unidentified or only tentatively identified. Each one has its own page with photos and the
observations recorded for it, such as colour, luster, hardness, streak, specific gravity, size and weight, so that
geologists and other specialists can give their opinion on what it might be. Every specimen has a stable number
("specimen #142") that you can use when you refer to it.

## How this repository is maintained

This repository is generated. Nothing here is edited by hand:

- The site is produced by a private collection-management app, built from
  [diantris/rock-collection](https://github.com/diantris/rock-collection).
- **Publishing** regenerates all pages and data as a single commit and replaces the previous version.
- **Photos** (in `photos/`) are uploaded separately, resized for the web and stripped of EXIF metadata. Publishing again
  leaves them in place.
