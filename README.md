# Ramiro "Colo" Martinez — Personal Website

The source code for [ramiromartinez.com](https://ramiromartinez.com), the personal website of Ramiro "Colo" Martinez.

The site is a simple, dependency-free home for personal information, writing, reading notes, social profiles, and interviews. It is intentionally built with plain HTML and hosted on GitHub Pages.

## Local preview

Clone the repository:

```bash
git clone https://github.com/ramiro-mart/ramiro-colo-martinez.git
cd ramiro-colo-martinez
```

Start a local web server with Python:

```bash
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser.

Because the site has no build step or external dependencies, you can also open `index.html` directly in a browser for a quick preview.

## Editing the site

All page content lives in [`index.html`](./index.html). Update that file to change the bio, writings, book list, social links, or interviews.

The repository contains two files used by the live site:

```text
.
├── CNAME       # Custom domain used by GitHub Pages
└── index.html  # Website markup and content
```

## Deployment

The site is deployed through GitHub Pages from the `main` branch. Pushing a change to `main` updates the live website after GitHub Pages finishes publishing it.

The [`CNAME`](./CNAME) file connects the deployment to the custom domain `ramiromartinez.com`. Keep this file in the repository root when making changes.

## Built with

- HTML
- GitHub Pages
