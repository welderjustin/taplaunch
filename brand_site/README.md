# TapLaunch — Brand Site (Static)

Paths
- /home/owner/.openclaw/workspace/projects/nfc-sites/brand_site/index.html
- /home/owner/.openclaw/workspace/projects/nfc-sites/brand_site/styles.css
- Uses logo at: /home/owner/.openclaw/workspace/projects/nfc-sites/brand/taplaunch_logo_wordmark.svg

Deploy (Netlify drag‑and‑drop)
1) Zip the brand_site folder or drag it directly onto app.netlify.com
2) Netlify assigns a URL (e.g., https://something.netlify.app)
3) Add your custom domain if you have one, SSL auto‑enabled

Deploy (GitHub Pages)
1) Create a public repo and add brand_site contents at repo root
2) Settings → Pages → Deploy from branch: main / root
3) Your site appears at https://<username>.github.io/<repo>

Forms
- GitHub Pages: this repo is set to use Formspree (update the form action in `index.html` with your Form ID). A `thanks.html` page is included for redirects.
- Netlify: if deploying to Netlify, you can revert to Netlify Forms (remove the `action` and add `data-netlify="true"` + hidden `form-name`).

Logo
- Place your logo at `assets/logo.png` (both header and hero reference `./assets/logo.png`).

Next
- Replace placeholder tiles in “Recent Work” with real images
- Update package copy/pricing if needed
- Add Privacy/Terms pages if collecting form data
