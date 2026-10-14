# Emiliano Rizza — personal website

Source for a Quarto personal website intended for GitHub Pages.

## 1. Create the GitHub repository

Create a public repository named:

```text
YOUR_GITHUB_USERNAME.github.io
```

Then upload the contents of this folder to the repository root.

## 2. Enable GitHub Pages

In the repository:

1. Open **Settings → Pages**.
2. Under **Build and deployment**, select **GitHub Actions**.
3. Push to the `main` branch.
4. The workflow in `.github/workflows/publish.yml` will render the Quarto site and publish it.

## 3. Edit locally (optional)

Install Quarto from https://quarto.org, then from this folder run:

```bash
quarto preview
```

To render without preview:

```bash
quarto render
```

## 4. Before publishing

Recommended final edits:

- Add a professional photo only if you want one; the current design works without it.
- Add Google Scholar, ORCID, INSPIRE and GitHub profile links once you decide which accounts to use publicly.
- Replace or update the CV PDFs whenever the source documents change.
- When the Rényi and analytical Krylov projects become public preprints, move them from “Ongoing” to the main publication list.
- Add slides only when you are comfortable making them public.

## Structure

- `index.qmd` — homepage
- `research.qmd` — research overview
- `publications.qmd` — papers and ongoing manuscripts
- `talks.qmd` — selected talks, posters and schools
- `projects.qmd` — methods/portfolio-oriented project descriptions
- `cv.qmd` — compact CV and downloadable PDFs
- `contact.qmd` — contact page
- `styles.css` — custom styling
- `_quarto.yml` — site configuration
