# Sunlight Sober Living Foundation

Static GitHub Pages site for **Sunlight Sober Living Foundation** at `www.sunlightsoberliving.org`.

## Mission

Sunlight Sober Living Foundation supports people recovering from addiction with practical help: food, sober living support, recovery scholarships, transportation help, and connection to a caring community.

## Site structure

- `index.html` — single-page nonprofit landing page
- `styles.css` — responsive visual design
- `script.js` — mobile navigation and footer year
- `CNAME` — custom GitHub Pages domain
- `.nojekyll` — keeps GitHub Pages from running Jekyll processing

## Research notes used for content direction

The page is modeled after recovery scholarship and community giving themes: hopeful language, practical support, clear donation/partner calls-to-action, and simple application/referral pathways.

Useful donation/program targets to pursue:

- Walmart Spark Good Local Grants: local cash grants are described as supporting local organizations meeting community needs; grants range from $250 to $5,000. https://www.walmart.org/how-we-give/local-community-grants
- Walmart Spark Good nonprofit tools: local grants, round-up, registries, and space request tools. https://www.walmart.com/nonprofits
- Costco Charitable Giving: community giving information. https://www.costco.com/charitable-giving.html
- Herren Project recovery scholarship model: emphasizes recovery support and coaching as tools for sustainable recovery. https://herrenproject.org/recovery-scholarship/

## Deployment

This repo is intended for GitHub Pages. The custom domain is set in `CNAME` as:

```text
www.sunlightsoberliving.org
```

After GitHub Pages is enabled, configure IONOS DNS:

- `www` CNAME → `brookecshockley-svg.github.io`
- Apex/root `sunlightsoberliving.org` A records → GitHub Pages IPs:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`

Keep existing IONOS mail/MX records for `info@sunlightsoberliving.org` intact.
