# Salvador — Portfolio

A one-page portfolio site for Salvador (content creator). Static HTML/CSS/JS — no build step.

## Structure
- `index.html` — the page (nav, hero, about, portfolio, services, contact)
- `styles.css` — styling (blue theme)
- `assets/` — photos and video

## Run locally
Open a terminal in this folder and run a static server:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000

## Deploy (GitHub Pages)
Push to GitHub, then in the repo: **Settings → Pages → Source: `main` branch, `/root`**.
The site will be published at `https://inesdias028.github.io/SalvadorsPortfolio/`.

## Editing content
- **Text/copy:** edit directly in `index.html` (bio, services, captions).
- **Contact email:** replace `hello@example.com` in the "Say hello" link.
- **Social handle:** replace `@salvador` in the contact section.
- **Add photos/videos:** drop files in `assets/` and add a `<figure class="card">` in the portfolio grid.
