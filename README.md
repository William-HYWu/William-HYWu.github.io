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

The CV page uses `assets/img/resume-preview.png` for a browser-independent preview and links to the original PDF for download and accessible text. When replacing the PDF, regenerate the preview (requires PyMuPDF):

```bash
python3 -c 'import pymupdf; doc = pymupdf.open("assets/pdf/Resume_Haoyang_Wu.pdf"); doc[0].get_pixmap(matrix=pymupdf.Matrix(2, 2), alpha=False).save("assets/img/resume-preview.png")'
```
