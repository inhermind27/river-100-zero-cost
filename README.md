# River · 100 Zero-Cost Cases

Static personal archive for **爱赚钱的River / River** ([@he_xinhe](https://x.com/he_xinhe)): publicly logging 100 zero-cost ways to make money with Grok Bot.

- **Stack:** plain HTML + CSS (no build step, no paid SaaS)
- **Payments:** Gumroad only (this site never processes checkout)
- **Suggested GitHub repo name:** `river-100-zero-cost`

## Local preview

From this directory:

```bash
cd /workspace/money-projects/river-cases-site
python3 -m http.server 8080
```

Open `http://127.0.0.1:8080/` (or open `index.html` via `file://`).

## Site map

| Path | Purpose |
|------|---------|
| `index.html` | Hero, challenge, CTA to Case 001 + cases list |
| `cases/index.html` | Case table (001 filled; 002–100 slots) |
| `cases/001.html` | Case 001 EN + ZH notes, metrics, Gumroad + X links |
| `products.html` | Free pack + note on future paid tiers |
| `about.html` | Mission, no guarantees, contact via X |
| `css/style.css` | Cream / gold theme |
| `assets/yuanbao.jpg` | Brand mark |
| `CONTENT.md` | Suggested X bio + website URL placeholder |

## Publish with GitHub Pages (free)

### Option A — project site (`username.github.io/repo`)

1. Create a public repo named e.g. `river-100-zero-cost` on GitHub.
2. Push this folder as the repo root (the folder that contains `index.html`).

```bash
cd /workspace/money-projects/river-cases-site
git init
git add .
git commit -m "Initial River cases archive site"
git branch -M main
git remote add origin https://github.com/<YOUR_USERNAME>/river-100-zero-cost.git
git push -u origin main
```

3. GitHub → **Settings** → **Pages** → Source: **Deploy from a branch** → Branch `main` / folder `/ (root)` → Save.
4. Site URL (after build): `https://<YOUR_USERNAME>.github.io/river-100-zero-cost/`

If you use a project site under a subpath, relative links in this repo already work (`css/`, `cases/`, etc.). No base-href required.

### Option B — user site (`username.github.io`)

1. Create repo named `<YOUR_USERNAME>.github.io`.
2. Push these files to `main` (or `gh-pages` per your Pages settings).
3. URL: `https://<YOUR_USERNAME>.github.io/`

### Custom domain (optional, still free DNS you already own)

In Pages settings, add a custom domain and create the DNS records GitHub shows. Add a `CNAME` file at the repo root with your domain if needed.

### Jekyll note

This site is static HTML. A `.nojekyll` file is included so GitHub Pages does not run Jekyll processing.

## Gumroad (do not invent payments)

Live free product (Case 001):

https://inhermind.gumroad.com/l/vnkedg

Paid tiers (~$7 etc.) go on Gumroad when tested; then add the real URL on `products.html`.

## Updating Case 001 metrics

Edit `cases/001.html` (and the row on `cases/index.html`) when downloads / impressions / feedback are known. Keep zeros until you have real numbers.

## License / honesty

Experiment logs only. No income guarantees. Contact: X [@he_xinhe](https://x.com/he_xinhe).
