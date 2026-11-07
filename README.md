# SameDay Energy Counsel — website

Public website for SameDay Energy Counsel (Stephen Brownell), energy reviews quoted in hours and delivered in a day.

- `index.html` — the whole site in one self-contained file (exported from the Muse draft, name-explorer and internal notes removed 2026-11-07).
- `.nojekyll` — tells GitHub Pages to serve the file as-is.

## Deploy (GitHub Pages)

1. Create a public repo (e.g. `samedayenergycounsel`) and push this folder's contents to the `main` branch.
2. Repo Settings → Pages → Source: Deploy from a branch, branch `main`, folder `/ (root)`.
3. The site is live at `https://<username>.github.io/samedayenergycounsel/`.
4. Custom domain (once samedayenergycounsel.com is registered): add a `CNAME` file containing `samedayenergycounsel.com`, then point the domain's DNS at GitHub Pages (A records to GitHub's Pages IPs, or a CNAME to `<username>.github.io`) and enable "Enforce HTTPS" in Pages settings.

## Editing

The source of truth is the Muse draft (artifact `ai-law-firm-website`). After any change there, re-export and replace `index.html` here.
