# Keefer Law Firm - Tailwind CSS

This page recreates the supplied `design.jpg` using Tailwind CSS and the original image assets from the ZIP.

## Quick start

1. Open `index.html` in VS Code.
2. Open it in your browser with Live Server.
3. The page uses the Tailwind CDN, so you can see the design immediately.

## Local Tailwind 3.4.17 setup

If Tailwind is already installed in your project:

```bash
npm install
npm run build
```

Then replace the CDN link in `index.html` with:

```html
<link rel="stylesheet" href="./dist/output.css">
```

For development:

```bash
npm run dev
```

The layout is desktop-first to match the reference and includes a responsive mobile navigation and stacked sections.
