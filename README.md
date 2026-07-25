# Kennedy Binegar — Technical Writing Portfolio

Live site: **[kbinegar.github.io](https://kbinegar.github.io/)**

A personal portfolio site built to showcase technical writing samples, resume,
and background — structured like a small documentation site, with a sidebar
table of contents and numbered sections.

## Sections

- **01 / About** — background and focus areas
- **02 / Resume** — downloadable PDF plus inline experience highlights
- **03 / Portfolio** — writing samples, each as its own linked page
- **04 / Blog** — short posts on technical writing process and craft
- **05 / How I Built This** — notes on the site's own build, doubling as a
  writing sample in itself

## Stack

Plain HTML and CSS — no framework, no build step, no dependencies to install.
Hosted free on GitHub Pages, deployed straight from the `main` branch.

## Structure

```
index.html           → homepage with all five sections as anchors
style.css            → shared styling across every page
resume.pdf           → downloadable resume
samples/             → one HTML page per portfolio writing sample
blog/                → one HTML page per blog post
images/favicon/      → favicon assets
```

Each portfolio sample and blog post is a standalone page (not just a
scroll-anchor) so it has its own shareable URL — useful when linking a single
writing sample directly in a job application.

## Adding new content

**A new portfolio sample:**
1. Duplicate an existing file in `/samples` as a starting template
2. Update the content and `<title>`
3. Add a matching `<a class="card">` link to the Portfolio section in `index.html`

**A new blog post:** same pattern, using `/blog` instead.

## Local preview

No build step required — open `index.html` directly in a browser, or serve
the folder locally with:

```
python3 -m http.server
```

then visit `http://localhost:8000`.

## Deployment

Pushes to `main` publish automatically via GitHub Pages
(Settings → Pages → Source: `main` / root).
