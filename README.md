# nepsis-privacy

Static site for **Nepsis** — privacy, terms, FAQ, and support pages hosted on GitHub Pages.

## Pages

| URL | File |
|-----|------|
| `/` | `index.html` — landing |
| `/privacy/` | `privacy/index.html` |
| `/terms/` | `terms/index.html` |
| `/help/` | `help/index.html` |
| `/support/` | `support/index.html` |
| `/about/` | `about/index.html` |

## GitHub Pages setup

1. **Settings → Pages** → Deploy from branch `main` → `/ (root)`
2. **Custom domain:** `nepsis.app` (see `CNAME`) — configure DNS at your registrar:
   - `A` records → GitHub Pages IPs (see [GitHub docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site))
   - or `CNAME` `www` → `nartaboe.github.io` if using subdomain
3. Enable **Enforce HTTPS** after DNS propagates

Until `nepsis.app` DNS is live, pages are available at:

`https://nartaboe.github.io/nepsis-privacy/`

## App Store Connect URLs (after custom domain)

- Privacy Policy: `https://nepsis.app/privacy/`
- Terms of Use: `https://nepsis.app/terms/`
- Support URL: `https://nepsis.app/support/`

## Contact

nepsis.support@gmail.com
