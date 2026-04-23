# Overview

An online, fully static map of Middle Earth (deployed at 3rin.gs) served from `www/`. Most of the content is generated from spreadsheets, hand-drawn graphics, and SVG layouts, assembled with Python (PIL, NumPy, JSON) plus Inkscape, GIMP, and Django templates. Large bitmap components live outside the repo and are fetched via `make archive/components`.
