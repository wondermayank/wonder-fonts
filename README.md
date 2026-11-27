# WonderFonts

Free font pairing and typography design studio by Wondermayank. Static site: no build step, no server.
Live: https://fonts.wondermayank.in/

## Deploy
- **Cloudflare Pages:** create a project, upload this folder (or connect the repo), build command empty, output directory `/`.
- **Vercel:** import the repo or run `vercel --prod` in this folder. Framework preset: Other, no build command.
- Add your own `favicon.svg` and `og-image.png` (1200x630) to the root.
- Routing uses `#/hash` URLs, so no rewrite rules are needed.

## Search, AI and SEO files (all under Wondermayank)
`robots.txt`, `sitemap.xml`, `llms.txt`, `llms-full.txt`, `humans.txt`, `site.webmanifest`, `.well-known/security.txt`.
Update the dates inside them when you change the site. `llms-full.txt` lists the real templates, pairings and FAQ.

## Notes
- Terms and Privacy live at wondermayank.in/terms and wondermayank.in/privacy.
- Background removal runs in the browser with the files in `/ai/` (onnxruntime-web and the open U2-Net-P model, Apache-2.0). Keep that folder when deploying.
