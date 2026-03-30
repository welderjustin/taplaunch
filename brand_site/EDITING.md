# TapLaunch — Editing & Deploying (Netlify Quickstart)

What’s in this folder
- index.html — the page layout
- styles.css — colors, spacing, layout rules
- content/site.json — the text for hero, packages, and FAQ (easy edit)
- assets/logo.png — your logo
- admin/ — (optional) CMS files; we can enable later via GitHub backend

Fastest edit path (no CMS)
1) Edit content/site.json — change hero_title, hero_sub, packages, faq
2) Save, then re‑deploy: drag the brand_site folder to https://app.netlify.com/drop
3) Refresh your live URL

Common quick edits
- Change hero headline: content/site.json → hero_title
- Change package prices/bullets: content/site.json → packages
- Change FAQ: content/site.json → faq
- Change logo: replace assets/logo.png (same filename) and redeploy

Styling (optional)
- Colors, spacing, fonts: styles.css (variables at top; e.g., --blue, --black)

Going further (recommended)
A) Connect GitHub (auto‑deploys)
- Create a GitHub repo and put the contents of brand_site at the repo root
- In Netlify, “New site from Git” → connect repo → main branch
- Any push to GitHub auto‑updates your live site

B) CMS (later)
- Switch admin/config.yml backend to GitHub and enable GitHub OAuth with Netlify
- You’ll edit text/images from /admin in the browser, no code needed

Troubleshooting
- Netlify says “need index.html”: make sure index.html is at the top level of what you upload
- Logo not showing: ensure assets/logo.png is inside brand_site and index.html references ./assets/logo.png
- No changes after deploy: your browser may be caching; hard refresh (Ctrl/Cmd+Shift+R)
