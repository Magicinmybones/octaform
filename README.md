# Octaform

Static landing page for Octaform, packaged for Cloudflare Pages.

## Structure

- `public/index.html` — site markup, styles, and interactions
- `public/assets/` — fonts, imagery, and icons used by the page
- `wrangler.jsonc` — Cloudflare Pages deployment configuration

## Preview locally

```sh
npx wrangler@latest pages dev public
```

## Deploy

```sh
npx wrangler@latest pages deploy public --project-name octaform --branch main
```
