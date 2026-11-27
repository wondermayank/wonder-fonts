# WonderFonts

**Free font pairing and design studio by [Wondermayank](https://wondermayank.in/).**
Merge fonts, check how well they pair, then create posters, stickers and social designs and download them in one click. No account, no watermark, no server.

**Live site:** [fonts.wondermayank.in](https://fonts.wondermayank.in/)

---

## What you can do

- **Explore 1,892 Google Fonts** with live preview and search
- **Merge and pair fonts** and check a pairing score before you commit
- **Start from 29 editable templates** or begin with a blank canvas
- **Create posters, stickers, posts, stories and thumbnails**
- **Remove backgrounds in your browser** to make clean stickers (nothing is uploaded)
- **One-click download** in PNG, JPG, SVG (fonts embedded), PDF or CSS, free and with no watermark
- **Auto-save** in your own browser, so your work stays on your device

## Design sizes

| Size | Dimensions |
| --- | --- |
| Instagram Post | 1080 x 1080 px |
| Instagram Portrait | 1080 x 1350 px |
| Story / Reel | 1080 x 1920 px |
| YouTube Thumbnail | 1280 x 720 px |
| X / LinkedIn Post | 1200 x 675 px |
| Blog / OG Image | 1200 x 630 px |
| Presentation 16:9 | 1920 x 1080 px |
| Poster (A-series) | 1240 x 1754 px |
| Business Card | 1050 x 600 px |
| X / Twitter Header | 1500 x 500 px |

You can also enter a custom size.

## Privacy

WonderFonts is a static site. Your designs are saved in your browser (IndexedDB) and are never uploaded to a server. Background removal also runs fully in your browser.

## Tech

- Plain static site: HTML, CSS and JavaScript, no build step
- Hash routing (`#/path`), so no rewrite rules are needed
- Background removal with `onnxruntime-web` and the open U2-Net-P model (Apache-2.0), kept in `/ai/`

## Run it locally

```bash
git clone https://github.com/wondermayank/wonder-fonts.git
cd wonder-fonts
python -m http.server 8000
```

Then open `http://localhost:8000`. Any static file server works.

## Deploy

- **Cloudflare Pages:** create a project, connect this repo, leave the build command empty and set the output directory to `/`.
- **Vercel:** import the repo or run `vercel --prod`. Framework preset: Other, no build command.
- Add your own `favicon.svg` and `og-image.png` (1200 x 630) to the root.

## Project files

| File / folder | Purpose |
| --- | --- |
| `index.html` | The studio |
| `ai/` | Background removal model and runtime (keep this folder when deploying) |
| `assets/` | Images and static assets |
| `ttf-index.json` | Font index |
| `LICENSE-MIT`, `LICENSE-APACHE`, `NOTICE` | License files |
| `robots.txt`, `sitemap.xml`, `llms.txt`, `llms-full.txt`, `humans.txt`, `site.webmanifest`, `.well-known/` | Search, AI and SEO files |

Update the dates inside the SEO files whenever you change the site.

## License and credit

The code is **dual-licensed**. You can use it under either of:

- [MIT License](LICENSE-MIT)
- [Apache License 2.0](LICENSE-APACHE)

at your option. Both let you use, modify and share the code, but you **must keep the copyright notice and license** in every copy. If you pick Apache-2.0, you must also keep the [NOTICE](NOTICE) file.

If you use or fork this project, please give credit:

> Based on [WonderFonts](https://github.com/wondermayank/wonder-fonts) by [Wondermayank](https://wondermayank.in/)

**Fonts:** the fonts in the studio come from Google Fonts. Each font keeps its own license (mostly SIL Open Font License), so check a font's license before using it in a product.

## Contact

- Website: [wondermayank.in](https://wondermayank.in/)
- Contact: [wondermayank.in/contact](https://wondermayank.in/contact)
- Terms: [wondermayank.in/terms](https://wondermayank.in/terms)
- Privacy: [wondermayank.in/privacy](https://wondermayank.in/privacy)

Made with care by **Wondermayank** in India.
