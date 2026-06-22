# Gold Supply — Supplier Sync

A static HTML mockup of a Shopify-admin–style **Supplier Sync** interface for Gold Supply.

The entire prototype is a single self-contained `index.html` (inline CSS + JS). Images load from the Shopify CDN and fonts from Google Fonts — there are no local asset dependencies, so it deploys as a pure static site.

## Hosting (Vercel)

This repo is configured for zero-build static hosting on Vercel:

- `index.html` is the entry point, served at `/`.
- `vercel.json` enables clean URLs with no build step.

To deploy: import the repo at [vercel.com/new](https://vercel.com/new), keep the framework preset as **Other**, and deploy. No build command or environment variables are required.

## Local preview

Open `index.html` directly in a browser, or serve it:

```bash
npx serve .
```
