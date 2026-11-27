# WonderFonts

Free font pairing and typography design studio by Wondermayank. Static site: no build step, no server.

## Deploy
- **Cloudflare Pages:** create a project, upload this folder (or connect the repo), build command empty, output directory `/`.
- **Vercel:** import the repo or run `vercel --prod` in this folder. Framework preset: Other, no build command.
- Add your own `favicon.svg` and `og-image.png` to the root.
- Routing uses `#/hash` URLs, so no rewrite rules are needed.

## Notes
- Terms and Privacy live at wondermayank.in/terms and wondermayank.in/privacy.
- Background removal runs fully in the browser using files in `/ai/` (onnxruntime-web + the open U2-Net-P model, Apache-2.0). Keep that folder when deploying.
