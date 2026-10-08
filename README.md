# thakar.net

Website of the **Thakar Group**, the family institutional group of the Thakar family.

## Structure
- `index.html` – the full site (single page, no build step)
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
