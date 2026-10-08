# Alina Pilatova website

Standalone Russian-language landing page for psychologist Alina Pilatova.

## Development

```sh
npm ci
npm run build
```

The Astro source is in `src/pages/index.astro`; the finished page is published at `/alina-pilatova/` on the Ministry of Transformation GitHub Pages site. The `site/` directory is a static preview copy of the same page. GitHub Actions builds the Astro source and deploys `dist/` whenever changes are pushed to `main`.

Profile credentials remain editorial placeholders until confirmed by Alina.
