# James Moran Portfolio

This Quarto website contains my GIS, R, and environmental research portfolio.

## Edit and preview

Open **James Portfolio Website.Rproj** in RStudio or run the following command from the repository root with Quarto installed.

```sh
quarto preview
```

The homepage, About, and Contact pages are in the root. Project pages and the résumé page are in `projects/`. Maps and images are in `assets/`, and downloadable PDFs are in `files/`.

## Render

Run `quarto render` from the repository root. Quarto writes the website to `docs/`. Commit that folder with the source changes to keep the checked-in website in sync.

For a GitHub Pages deployment, use **Settings → Pages → Deploy from a branch** and select **main** and **/docs** when GitHub Pages is available for the repository.
