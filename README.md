# thakar.net

Website of the **Thakar Group**, the family institutional group of the Thakar family.

## Structure
Static site, no build step. Every page shares `styles.css`; the header and footer are repeated in each page, so edit them in all of them.
- `index.html` – Home
- `about.html` – About, the family, governance, principles
- `companies.html` – every group company, with a detail section each
- `ai.html` – the shared AI layer across the group
- `contact.html` – contact desks
- `404.html` – not-found page
- `robots.txt`, `sitemap.xml` – for search engines
- `vercel.json` – serves `/about` etc. without `.html`
- `CNAME` – custom domain for GitHub Pages (`thakar.net`)

## Deploy on Vercel
1. vercel.com → Add New → Project → import `thakar.net-webiste-` (framework: Other, no build command).
2. Project → Settings → Domains → add `thakar.net` and `www.thakar.net`.
3. At your domain registrar set:
   - `A` record `@` → `76.76.21.21`
   - `CNAME` record `www` → `cname.vercel-dns.com`
   (The www ↔ bare-domain redirect is set in Vercel → Settings → Domains, not in `vercel.json`.)

## Deploy on GitHub Pages (alternative)
1. Push this repo to GitHub.
2. Settings → Pages → Source: `main` branch, root folder.
3. At your domain registrar, point `thakar.net` to GitHub Pages
   (A records 185.199.108.153, .109.153, .110.153, .111.153, and a `www` CNAME to `<user>.github.io`).

## To fill in
- Roles for Vivek Thakar and Meenakshi Thakar (currently "Family Council")
- Contact email (currently `contact@thakar.net`)
