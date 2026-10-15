# Junwon Lee

Personal academic homepage: https://junwonlee00.github.io/

Based on [Jon Barron's original HTML template](https://github.com/jonbarron/jonbarron.github.io).
See [TEMPLATE_SOURCE.md](TEMPLATE_SOURCE.md) for source provenance.

## Editing

- `index.html`: name, introduction, contacts and future publication entries.
- `stylesheet.css`: original typography and layout, followed by small custom adjustments.
- `.nojekyll`: serves this as a plain static site.

There is no build command or JavaScript dependency. GitHub Pages publishes the
root of `main`. Do not copy the template author's `CNAME`, analytics, portrait,
CV or publication content.

## Profile photo

The left side of the profile currently contains a neutral photo placeholder.
When the portrait is ready, replace that `div` with an `img` using the
`profile-photo` class, the local image path and `alt="Junwon Lee"`.
The profile sits beside the introduction on desktop and above it on mobile.
Email and GitHub links appear directly below the introduction.

## Adding a publication

When a paper is public, add a presentation table inside the existing `Research`
section. Each `tr` should contain a `publication-image` cell and
a `publication-content` cell. Use the original `.papertitle` class for its title.
The stylesheet already stacks these cells on narrow screens.

Include the real thumbnail, title, authors, venue/year and available Paper,
Project and Code links. Bold Junwon Lee's name in the author list. Add descriptive
alternative text to the image. Do not publish example papers or unavailable links.

Place a paper's project page at `projects/<paper-slug>/index.html` and link to
`/projects/<paper-slug>/`. Each project page can introduce the paper, show its
method and results, link to resources, and provide BibTeX. Create these pages
when the actual paper and approved public materials are ready.
