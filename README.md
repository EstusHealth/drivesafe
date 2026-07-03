# DriveSafe DriveAware Assessment

A self-contained, single-page assessment tool. Everything (markup, styles, and
logic) lives in `index.html`, and all data is stored client-side in the browser
via `localStorage` and `indexedDB` — there is no backend or build step.

## Hosting on Vercel

This is a static site, so no framework or build command is required.

### Deploy

1. Import this repository into Vercel (or run `vercel` from the CLI).
2. When prompted for a framework preset, choose **Other**.
3. Leave **Build Command** empty and set **Output Directory** to the repo root
   (the default). Vercel serves `index.html` at `/` automatically.

`vercel.json` sets `cleanUrls` and a few baseline security headers.

### Local preview

Open `index.html` directly in a browser, or serve the folder:

```bash
npx serve .
```
