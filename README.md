# TanziTech Blog (GitHub Pages)

Static blog with hand-authored HTML articles.

## Quick Deploy
1) Create a new repo on GitHub (e.g., `tanzitech-blog`).
2) Upload all files from this folder (including `.nojekyll` and `CNAME`).
3) Go to **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main** (root).
4) Wait for Pages to build, then open: `https://blog.tanzitech.com/` (or your GitHub Pages URL).

### Custom Domain (Cloudflare)
- DNS on Cloudflare: create a **CNAME** record  
  - **Name**: `blog`  
  - **Target**: `<your-username>.github.io`  
  - **Proxy**: **ON** (orange cloud)
- In GitHub repo → Settings → Pages: set **Custom domain** to `blog.tanzitech.com` and enable **Enforce HTTPS**.

### Notes
- `CNAME` file locks the domain to `blog.tanzitech.com`. Edit it if you prefer another domain.
- `sitemap.xml` and `robots.txt` are included for SEO.
- `404.html` gracefully links users back to Home.
