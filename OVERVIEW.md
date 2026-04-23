# Overview

3rin.gs is an online map of Middle Earth. The site is published as a fully static front-end from the `www/` and `build/` directories on <http://3rin.gs/>.

Most content is generated from spreadsheets, hand-drawn graphics, and SVG layouts, then composited with Python Imaging Library, Inkscape, and Gimp. Django templates are used to render articles and data-driven HTML.

Large bitmap components (geography and label layers) live outside this repo and can be fetched with `make archive/components`; original scans via `make archive/sources`.

See `README.md` for setup dependencies and asset fetch targets.
