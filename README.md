# Foundational Statistics for Psycholinguistics

This repository is a starter template for an online markdown book built with [Quarto](https://quarto.org/). The book is organized around seven teaching modules, with placeholders for explanations, examples, exercises, datasets, and reporting guidance.

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

1. Create a new GitHub repository.
2. Update `repo-url` in `_quarto.yml`.
3. Push this folder to GitHub.
4. In the GitHub repository, go to `Settings > Pages`.
5. Set the source to `GitHub Actions`.
6. Push to `main` or run the `Publish Quarto Book` workflow manually.

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
git push
```
