# Faizal Infotech — ERP / Odoo / DevOps Website

Premium bilingual static website for **English + Arabic**, prepared for GitHub Pages.

## Site structure

- `site/index.html` — automatic language selector
- `site/en/` — English website
- `site/ar/` — Arabic RTL website
- `site/404.html` — portable GitHub Pages 404
- `.github/workflows/deploy-pages.yml` — automatic GitHub Pages deployment

## Deploy on GitHub Pages

1. Push the contents of this repository to the `main` branch.
2. Open **Settings → Pages**.
3. Under **Build and deployment → Source**, select **GitHub Actions**.
4. Open the **Actions** tab and wait for `Deploy website to GitHub Pages` to complete.
5. The site will be available at `https://Faizalemam.github.io/faizal-infotech-website/`.

## Language behavior

- Saudi/Riyadh timezone or Arabic browser preference → Arabic.
- India/Kolkata timezone → English unless Arabic is explicitly preferred.
- User choice in `EN | العربية` is saved in local storage and takes priority on the next visit.
- Arabic version uses RTL layout.

## Production checklist

- Add official logo, phone, email and WhatsApp CTA.
- Connect the contact form to Odoo CRM/email/backend.
- Add real case studies and project portfolio.
- Configure Search Console, analytics and final sitemap after the public URL/domain is known.
- Revalidate current ZATCA/GST/privacy requirements before publishing compliance claims.


Pages publishing source: `main` → `/(root)`.
