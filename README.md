# Divyank K Pawar Portfolio

This portfolio is configured to publish with **GitHub Pages only**. The GitHub Actions workflow builds the app as a static site and deploys the generated `dist/client` folder to Pages.

## Publish on GitHub Pages

1. Push this repository to GitHub.
2. In the GitHub repository, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. Push to the `main` or `master` branch, or run the **Deploy to GitHub Pages** workflow manually from the **Actions** tab using `main` or `master`.
5. If you run the workflow from another branch, the build will run but deployment will be skipped to avoid GitHub Pages environment protection errors.
6. After the workflow finishes on `main` or `master`, GitHub will show the public Pages URL in **Settings → Pages** and in the workflow deployment summary.

## Local development

```bash
npm install
npm run dev
```

## Build locally

```bash
npm run build
```

The static site output for GitHub Pages is generated in `dist/client`.
