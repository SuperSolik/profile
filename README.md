# Sergei Petrov's CV

This repository contains Sergei Petrov's CV in LaTeX format and provides a simple web deployment via GitHub Pages.

## Files

- `cv.tex`: LaTeX source file for the CV
- `template.tex`: LaTeX template used by cv.tex
- `index.html`: Landing page for the web deployment

## Deployment

The CV is automatically deployed to GitHub Pages on every push to the `main` branch. The deployment process:

1. Compiles `cv.tex` to `cv.pdf` using LaTeX
2. Creates a `pages` directory with `cv.pdf` and `index.html`
3. Deploys the static site to GitHub Pages

The live CV can be accessed at: https://supersolik.github.io/profile/

## Local Development

To build the PDF locally:

```bash
pdflatex cv.tex
```

To view the web version locally, open `index.html` in a browser.
