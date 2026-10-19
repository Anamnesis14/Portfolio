# ThinkBlank Photography

Responsive, buildless photography portfolio. Website files are in `dist/`.

## Preview

Run `python3 -m http.server 8080 --directory dist` and open http://localhost:8080.

## Deploy to Cloudflare Pages

Authenticate from your own terminal:

```sh
npx wrangler@latest login
npx wrangler@latest pages project create thinkblank --production-branch main
npx wrangler@latest pages deploy dist --project-name thinkblank --branch main
```

If the Pages project already exists, skip project creation. Use a different project name if needed.

For Git integration, connect the repository in Cloudflare Pages, select no framework, leave the build command blank, and set the output directory to `dist`.

## Content still needed

Replace the labeled photograph placeholders with your images and descriptive alt text. Add your biography and contact details before public launch.
