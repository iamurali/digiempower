# Digi Empower India

Marketing website for **Digi Empower India** — digital marketing, ecommerce solutions, franchise expansion, and business growth services across Hyderabad, Andhra Pradesh & Telangana.

## Live Site

- **GitHub Pages**: [iamurali.github.io/digiempower](https://iamurali.github.io/digiempower)
- **Custom Domain** (when configured): [digiempower.in](https://digiempower.in)

## Project Structure

```
index.html       — Main single-page website
404.html         — Custom 404 error page
CNAME            — Custom domain configuration (digiempower.in)
robots.txt       — Search engine crawl directives
sitemap.xml      — Sitemap for SEO
.nojekyll        — Disables Jekyll processing on GitHub Pages
assets/
  favicon.svg    — SVG favicon
```

## Deployment

This site is deployed via **GitHub Pages** from the `main` branch.

### Using GitHub Pages (github.io)

1. Go to **Settings > Pages** in your GitHub repo
2. Set **Source** to `Deploy from a branch`
3. Select `main` branch, `/ (root)` folder
4. The site will be live at `https://iamurali.github.io/digiempower`

> **Note**: If you want to use the `github.io` URL without a custom domain, **delete or rename the `CNAME` file** first. The `CNAME` file tells GitHub Pages to serve from `digiempower.in`, which will fail if DNS is not configured.

### Connecting a Custom Domain

1. Keep the `CNAME` file with your domain (e.g., `digiempower.in`)
2. Configure DNS at your domain registrar:
   - **A records** pointing to GitHub Pages IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - **CNAME record** for `www` pointing to `iamurali.github.io`
3. In GitHub repo Settings > Pages, enter your custom domain
4. Enable **Enforce HTTPS**

### Multiple Domains

To use alternate domains (`digiempowerindia.com`, `digiempowerindia.in`), configure them as redirects to the primary domain (`digiempower.in`) at your DNS provider.

## SEO

The site includes:
- Comprehensive meta tags (title, description, keywords, robots)
- Open Graph and Twitter Card meta tags
- JSON-LD structured data (Organization, LocalBusiness, WebSite)
- Geographic meta tags targeting Andhra Pradesh & Telangana
- `robots.txt` and `sitemap.xml`
- Multi-region `areaServed` in structured data (Nellore, Hyderabad, Vijayawada, Visakhapatnam, Tirupati)

## Tech Stack

- **HTML5** with semantic markup
- **Tailwind CSS** (via CDN)
- **Google Fonts** (Manrope, Inter)
- **Material Symbols** (Google)
- Vanilla JavaScript (no frameworks)

## Contact

- Phone: [83092 42377](tel:+918309242377)
- Email: [connect@digiempowerindia.com](mailto:connect@digiempowerindia.com)
- WhatsApp: [Chat](https://wa.me/918309242377)
- Location: Near RTC Bus Stand, Nellore, A.P.
