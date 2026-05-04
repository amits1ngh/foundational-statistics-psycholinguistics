# Foundational Statistics in (Psycho)linguistics

This repository contains the source files for an online Quarto book on foundational statistics in psycholinguistics. The book is organized around seven modules, with explanations, examples, exercises, datasets, and reporting guidance.

Repository:

```text
https://github.com/amits1ngh/foundational-statistics-psycholinguistics
```

Expected GitHub Pages site:

```text
https://amits1ngh.github.io/foundational-statistics-psycholinguistics/
```

## Structure

```text
.
  _quarto.yml
  index.qmd
  chapters/
  data/
  examples/
  exercises/
  assets/
  references.bib
  styles.css
  .github/workflows/publish.yml
```

## Local Preview

Install Quarto, then run:

```bash
quarto preview
```

To render the static site locally:

```bash
quarto render
```

The rendered HTML book will be created in `_book/`.

## Publish on GitHub Pages

1. Push this folder to `https://github.com/amits1ngh/foundational-statistics-psycholinguistics`.
2. In the GitHub repository, go to `Settings > Pages`.
3. Set the source to `GitHub Actions`.
4. Push to `main` or run the `Publish Quarto Book` workflow manually.
5. After the workflow finishes, open `https://amits1ngh.github.io/foundational-statistics-psycholinguistics/`.

## Editing Chapters

Each module lives in `chapters/` as a `.qmd` file. Quarto Markdown works like regular Markdown, with optional support for executable code cells, citations, callouts, figures, tables, and cross-references.

Start by replacing the placeholders in each chapter with:

- Course explanations.
- Psycholinguistic examples.
- R or Python code.
- Student exercises.
- Datasets or links to datasets.
- Reporting examples.

## Suggested Development Workflow

```bash
git status
quarto preview
git add .
git commit -m "Create initial course book scaffold"
git remote add origin https://github.com/amits1ngh/foundational-statistics-psycholinguistics.git
git push -u origin main
```
