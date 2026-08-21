# secslayer.github.io

Personal site — [secslayer.github.io](https://secslayer.github.io)

Static, single page, no build step and no dependencies: `index.html` carries its own CSS and has
no external requests, so it renders identically offline and can't break from a CDN going away.

## Structure

- `index.html` — the whole site
- `resume.pdf` — downloadable resume, linked from the header

## Editing

Edit `index.html` and push to `main`; GitHub Pages redeploys automatically.

Colours are CSS custom properties defined once at the top (`:root`), with dark-mode overrides
directly beneath. Change a value there rather than hunting through rules.

## One rule this page follows

Every claim links to where it can be checked, or says plainly that it can't — the status chips
(`earned` / `prep completed` / `preprint in prep` / `reproduced`) exist so nothing reads as more
finished than it is. Borrowed from [jlens-fuzz](https://github.com/secslayer/jlens-fuzz)'s own
contributing rule: a number with no provenance does not go in the paper. If you edit this page,
keep that property.

## License

[MIT](LICENSE) — for the site's **code**: the markup, CSS, and layout in `index.html`. Reuse the
template freely.

**Not covered:** the written content (biography, project descriptions, wording) and `resume.pdf`
are personal materials, not licensed for reuse. MIT is a software licence and is not intended to
put a person's CV or professional history into the public domain. Take the structure and styling
if they're useful; write your own words.
