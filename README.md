# javai.ch

The source for [javai.ch](https://javai.ch/) — a multilingual static website covering AI regulation and compliance in Switzerland. It is the Swiss-focused companion to [javai.org](https://javai.org/), which hosts the technical open-source projects.

The site is published in four languages: English, German (Swiss orthography), French, and Italian.

## Prerequisites

- [Hugo extended edition](https://gohugo.io/installation/) (latest version)
- Git

## Getting started

Clone the repository and run the local development server:

```sh
git clone https://github.com/javai-org/javai-ch.git
cd javai-ch
hugo server
```

The site will be available at `http://localhost:1313/`. Hugo watches for file changes and reloads automatically.

## Content structure

Content lives under `content/`, with a subdirectory per language (`en/`, `de/`, `fr/`, `it/`). New content must be created in all four languages.

See `CLAUDE.md` for content guidelines, including the Swiss German orthography rules.

## Contributing workflow

1. Create a branch from `main` with a descriptive name, e.g. `post/march-compliance-update` or `regulation/new-finma-circular`
2. Add or edit content on that branch
3. Push the branch and open a pull request
4. A repository administrator reviews the content and merges to `main` if approved

Merging to `main` triggers deployment automatically — no manual publish step is needed.

## Deployment

The site is built and deployed to GitHub Pages via a [GitHub Actions workflow](.github/workflows/deploy.yml). On every push to `main`:

1. Hugo builds the site with `--minify`
2. The built output is deployed to GitHub Pages

The site is served at [javai.ch](https://javai.ch/) with HTTPS enforced.
