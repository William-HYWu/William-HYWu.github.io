# Haoyang Wu — personal website

Academic website built with [al-folio](https://github.com/alshedivat/al-folio), with a custom responsive layout and About, Publications, and Teaching tabs. A research timeline and direct PDF CV link appear on the homepage. Deployed through GitHub Pages.

## Local development

```bash
bundle install
npm ci
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000/`.

## Content

- Homepage: `_pages/about.md`
- Research timeline (homepage and Research page): `_includes/research-experience.liquid`
- Teaching: `_pages/teaching.md`
- Publications: `_bibliography/papers.bib`
- Page layout and styles: `_layouts/academic.liquid`, `assets/css/academic.css`
- Publication layout: `_layouts/paper.liquid`
- Social links: `_data/socials.yml`
- Profile and publication images: `assets/img/`
- Résumé: `assets/pdf/Resume_Haoyang_Wu.pdf`
- Unlisted web CV: `_pages/cv.md`, with publications rendered by `_layouts/cv-paper.liquid`

The downloadable PDF is linked from the homepage. The unlisted web CV remains available at `/cv/` and uses `_bibliography/papers.bib`, shared with the Publications page. Keep both CV versions up to date when changing education, roles, awards, or teaching experience.
