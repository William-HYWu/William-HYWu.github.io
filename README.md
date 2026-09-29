# Haoyang Wu — personal website

Academic website built with [al-folio](https://github.com/alshedivat/al-folio), with a custom responsive layout and separate About, Research, Publications, Teaching, and CV pages. Deployed through GitHub Pages.

## Local development

```bash
bundle install
npm ci
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000/`.

## Content

- Homepage: `_pages/about.md`
- Research experience (homepage and Research page): `_includes/research-experience.liquid`
- Teaching: `_pages/teaching.md`
- Publications: `_bibliography/papers.bib`
- Page layout and styles: `_layouts/academic.liquid`, `assets/css/academic.css`
- Publication layout: `_layouts/paper.liquid`
- Social links: `_data/socials.yml`
- Profile and publication images: `assets/img/`
- Résumé: `assets/pdf/Resume_Haoyang_Wu.pdf`
- Web CV: `_pages/cv.md`, with publications rendered by `_layouts/cv-paper.liquid`

The CV is rendered as selectable HTML using the site's shared typography, colors, and responsive layout. Its publications use `_bibliography/papers.bib`, shared with the Publications page. Keep the web CV and downloadable PDF up to date when changing education, roles, awards, or teaching experience.
