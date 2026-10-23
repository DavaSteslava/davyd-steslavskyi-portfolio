# Davyd Steslavskyi — Developer

Single-page portfolio hosted with GitHub Pages. The supplied page is kept as
`site/index.html`; no build step is needed. Its photos are embedded in the
HTML. Google Fonts and Tailwind CSS are loaded from their CDNs.

## Publish

1. Sign in to GitHub and create a **public**, empty repository named
   `davyd-steslavskyi-portfolio` under `DavaSteslava`.
2. From this folder, run:

   ```sh
   git init -b main
   git add site/index.html README.md .github/workflows/pages.yml
   git commit -m "Add portfolio site"
   git remote add origin https://github.com/DavaSteslava/davyd-steslavskyi-portfolio.git
   git push -u origin main
   ```

3. In the repository, open **Settings → Pages** and select **GitHub Actions**
   as the build and deployment source if it is not already selected.
4. Wait for the **Deploy portfolio to GitHub Pages** workflow in the **Actions**
   tab to finish successfully.

The shareable site URL will be
<https://davasteslava.github.io/davyd-steslavskyi-portfolio/>.
Subsequent pushes to `main` deploy automatically.
