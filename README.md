# NISSS Benefits — Check what you can claim

A simple, accessible government service that helps people in Barbados find out which
**National Insurance** benefits they may be able to claim from the National Insurance
and Social Security Service (NISSS).

Built static (HTML, CSS, a little JavaScript), using the Government of Barbados Design
System, and following GDS-style service design: start with a user need, one thing per
page, plain language, and progressive enhancement.

## Live site

https://govtech-bb.github.io/nisss-benefits/

## Pages

- `dist/index.html` — start page (what the service does, who it's for, "Start now")
- `dist/check.html` — eligibility checker (a few questions → a tailored list of benefits)
- `dist/benefits.html` — full A–Z reference of every benefit, with rates, conditions and documents

## Run locally

Any static file server pointed at the `dist/` folder, for example:

```bash
npx serve dist
```

Then open the printed URL.

## Deployment

Pushes to `main` are published to GitHub Pages automatically by
`.github/workflows/deploy.yml`, which serves the contents of `dist/`.

## Source of content

National Insurance and Social Security Service (NISSS),
*Registration, Benefits and Claims Overview* (April 2026).
