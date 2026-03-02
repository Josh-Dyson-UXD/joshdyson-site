# JoshDyson.com (static)

A minimal, Apple-inspired single-page site (plain HTML/CSS) ready for GitHub + Vercel.

## Quick start (local)
Just open `index.html` in your browser.

## Deploy on Vercel (recommended)
1. Create a GitHub repo and push these files.
2. In Vercel: **New Project** → import your repo.
3. Framework preset: **Other**
4. Build command: **(none)**
5. Output: **(root)**

Vercel will auto-detect this as a static site.

## Custom domain
In Vercel: Project → Settings → Domains → add:
- `joshdyson.com`
- `www.joshdyson.com`

Then update DNS at your registrar (GoDaddy):
- A record `@` → `76.76.21.21`
- CNAME `www` → `cname.vercel-dns.com`

⚠️ Leave your Google Workspace **MX records** unchanged so email keeps working.

## Personalize
- Update LinkedIn / Instagram URLs in `index.html`
- Update email and location
- Replace `favicon.svg` if you want


## Social preview (OG image)
This repo includes `og.png` (1200×630) and meta tags are already set in `index.html`.


## Portrait
This repo includes `josh.webp` and `josh.png` used in the hero.
