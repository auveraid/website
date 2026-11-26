# Aureva — Website

Static site hosted with GitHub Pages.

- `index.html` — main (desktop) website
- `mobile/index.html` — mobile version (screens ≤ 800px are redirected here automatically; add `?desktop` to the URL to skip the redirect)

## GitHub Pages + custom domain
1. Settings → Pages → Source: **Deploy from a branch**, Branch: `main` / `(root)`.
2. Under **Custom domain**, enter your domain and save (GitHub creates a `CNAME` file).
3. At your DNS provider: for an apex domain add A records `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`; for `www` add a CNAME to `auveraid.github.io`.
4. Once the certificate is issued, enable **Enforce HTTPS**.
