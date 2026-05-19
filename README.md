# blog-images

Hosting for images embedded in Michał's blog post drafts and review docs.

Each post's figures live under their own directory and are referenced by stable `raw.githubusercontent.com` URLs from gists, Craft docs, and similar review surfaces during drafting.

Files here are not the published artifacts — those live in the Astro site's `public/assets/`.
This repo just gives the review tooling something with a proper `image/*` content-type to fetch from.

Posts:

- `gradient-intuitions/` — figures for *Why the gradient is a list of partial derivatives*.
  PNGs (raster, used by Craft) and source SVGs are kept side by side.
