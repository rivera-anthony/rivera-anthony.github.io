# Anthony Rivera — Academic Website

Quarto source for an academic portfolio in econometrics, monetary economics,
and applied policy research.

## Before publishing

1. Replace every `YOUR-...` value and every link pointing to `#`.
2. Add `assets/Anthony-Rivera-CV.pdf`.
3. Update education, experience, dates, and language proficiency.
4. Add only papers, figures, code, and data that may be shared publicly.
5. Update `site-url` in `_quarto.yml`.

Find remaining placeholders with:

```bash
rg 'YOUR-|Add |Insert |\\[University|\\[Prior|\\[Position|href="?#"?' .
```

## Preview locally

Install Quarto, open a terminal in this directory, and run:

```bash
quarto preview
```

## Publish with GitHub Pages

Push the project to a GitHub repository whose default branch is `main`. The
included workflow renders the site and publishes it to the `gh-pages` branch.
In the repository's **Settings → Pages**, select **Deploy from a branch**, then
choose the `gh-pages` branch and the root directory.

