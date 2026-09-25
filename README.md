# Shamima Sultana — QA Portfolio

Personal QA portfolio and tutorial site. Plain HTML/CSS/JS — no build step, no dependencies.

## What's here (pilot batch)
- `index.html`      — portfolio home page
- `K6Hub.html`      — k6 learning path
- `K6.html`         — JavaScript for k6 (module 01)
- `K6Course.html`   — k6 course (modules 02–08)
- `assets/`         — image(s)

More pages (Playwright, SQL, Manual, API, etc.) will be added the same way.

## Publish on GitHub Pages
1. Create a repository named exactly:  `ShamimaSultanaMiley.github.io`
2. Upload every file here, keeping the folder structure (index.html at the top).
3. Commit to the `main` branch.
4. On GitHub: **Settings → Pages → Source: Deploy from a branch → Branch: main → /(root) → Save**.
5. Wait 1–2 minutes, then open:  https://shamimasultanamiley.github.io

Every push to `main` updates the live site.

## Test locally first (optional)
From this folder:
    python -m http.server 8000
Then open http://localhost:8000 in your browser.

## Notes
- Menu links to pages not in this batch yet (Playwright, SQL, News, …) will show
  "404" until those pages are added. That's expected during the pilot.
- Best viewed on a desktop for now; a mobile-friendly pass comes later.
