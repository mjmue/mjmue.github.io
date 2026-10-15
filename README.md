# Michael Mueller

Personal research website for Michael Mueller, Copenhagen Business School.

Intended public address: https://michaeljmueller.org/
Repository: https://github.com/mjmue/mjmue.github.io

## Editing

- Edit the biography, research entries, and contact information in `index.html`.
- Edit typography, colors, and spacing in `styles.css`.
- Click each research category heading to open or close it. Only Peer-Reviewed Publications starts open; Book Chapters and Selected Work in Progress start closed. Add or remove `open` on a category’s `<details class="research-group">` tag to change its initial state. Abstracts open independently.
- External links and PDFs use `target="_blank" rel="noopener"` to open in a new tab. Use `aria-describedby="new-tab-note"` to announce this to screen readers. Keep navigation and email links without a target.
- Replace `assets/cv.pdf` with a fresh PDF export when updating the CV.
- Keep `assets/fonts/` with the website; it includes Latin Modern fonts and their licenses.
- Keep `CNAME` at the repository root to preserve the custom domain.

This is a static HTML website with no build step. The canonical, Open Graph, and structured-data URLs in `index.html` should match the public domain.

## Hosting

GitHub Pages publishes this repository from `main`, using the repository root, once enabled in Settings → Pages. Register and verify domain ownership before configuring the custom domain.

See [GitHub's custom-domain instructions](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).

Once publishing is enabled, commits to the publishing branch update the website.
