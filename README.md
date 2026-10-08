# Seth Jenkins — Author Website

A responsive, static author website for the existing collection of fantasy, poetry, and philosophy books. It uses plain HTML and CSS, so there is no build step or package installation.

## Preview locally

Open `index.html` in a browser.

## Update before launch

Search the files below for the visible editorial notes and sample links:

- **Author bio:** Replace the short bio and the “Add Seth’s approved author bio here” prompt in `index.html` with approved details.
- **Things Unsaid cover:** Replace `assets/cover-things-unsaid.svg` with approved cover art. Keep its filename or update both image references in `index.html`.
- **Book description:** Replace “Add the approved description…” in `index.html` with publisher-approved copy.
- **Purchase destination:** Add a retailer link beside the purchase placeholder in the book card in `index.html`.
- **Contact and social links:** Replace `YOUR_EMAIL@example.com`, `YOUR_USERNAME`, and the sample Instagram, Goodreads, and Threads links in `index.html`. Remove any profiles Seth does not use.
- **Site metadata:** Review the page description and social sharing text in the `<head>` of `index.html`.

The placeholders are intentionally visible so unfinished author and book details are easy to spot. Confirm all of them are replaced before sharing the live site.

## Publish on GitHub Pages

The workflow in `.github/workflows/pages.yml` packages the repository root and deploys it whenever changes reach `main`. The site is designed for the repository path at:

`https://sethj508.github.io/Seth-Jenkins/`

In the repository’s **Settings → Pages**, select **GitHub Actions** as the build and deployment source if it is not already selected. A push to `main` then starts the deployment workflow. Check its latest run under **Actions → Deploy author website**; the live URL is reported in the successful deployment summary.

## Files

- `index.html` — page structure and editable book, biography, contact, and social content
- `styles.css` — responsive styles
- `assets/` — editable placeholder book cover and favicon
- `.github/workflows/pages.yml` — GitHub Pages deployment
