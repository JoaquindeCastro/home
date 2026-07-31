# NOVUS Innovations Website

A complete, responsive website for NOVUS Innovations, rebuilt from the ground up as a distinctive youth-innovation platform rather than a generic organization template.

## Included

- Modern editorial visual identity and custom NOVUS brand mark
- Responsive desktop, tablet, and mobile layouts
- About, programs, methodology, publications, team, partners, recruitment, and partnership sections
- Dedicated `/publication/` archive
- Accessible navigation, reduced-motion support, semantic structure, and keyboard skip link
- SEO metadata, sitemap, crawler rules, favicon, web manifest, and custom 404 page
- Vercel, Netlify, and GitHub Pages-ready static deployment
- No framework, package installation, or build command required

## Recommended deployment: Vercel

1. In Vercel, select **Add New → Project**.
2. Import `JoaquindeCastro/home` from GitHub.
3. Set Framework Preset to **Other**.
4. Leave Build Command empty and Output Directory as `.`.
5. Deploy.
6. Open **Settings → Domains** and add `enovusinnovations.org`.
7. Apply the DNS records shown by Vercel at the registrar that manages the domain.

## Netlify alternative

Import this repository, leave Build Command empty, set Publish Directory to `.`, deploy, and add `enovusinnovations.org` under Domain Management.

## GitHub Pages alternative

Enable GitHub Pages from the `main` branch and repository root. The included `CNAME` file already identifies `enovusinnovations.org` as the production domain.

## Maintaining the site

- Page content: `index.html`
- Publications archive: `publication/index.html`
- Visual system and responsive rules: `styles.css`
- Navigation and reveal interactions: `script.js`
- Brand assets: `assets/`

## Current contact routes

- Email: `team@novusinnovations.org`
- Recruitment: `http://join.novusinnovations.org`
- Instagram: `https://www.instagram.com/novus.innovations/`
