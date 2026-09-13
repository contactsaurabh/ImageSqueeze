# ImageSqueeze — Free Online Image Compressor (JPG, PNG, WebP)

**ImageSqueeze** is a free, private, browser-based image compressor. Drop in a JPG, PNG, or WebP photo, adjust the quality, and download a smaller file — instantly, with no upload, no signup, no watermark, and no server involved. Great for shrinking photos for a website, email attachment, WhatsApp, resume upload, or any form with a file-size limit.

🔗 **Live demo:** https://image.trucirkl.com/

## Features
- Compress **JPG/JPEG**, **PNG**, and **WebP** images
- Adjustable quality slider + one-click presets (Best quality / Balanced / Smaller file / Tiny file)
- Resize by maximum dimension for even smaller files
- Live before/after file-size comparison
- Drag & drop, click-to-browse, or paste an image from the clipboard
- **100% client-side** — your images never leave your device or touch a server
- No install, no build step, no dependencies, no account needed

## How to use
1. Open `index.html` in any modern browser (double-click it, or drag it into a browser tab) — or visit the hosted live demo.
2. Drag & drop an image onto the page (or click to choose one, or paste from clipboard).
3. Adjust the **Quality** slider or pick a preset (Best quality / Balanced / Smaller file / Tiny file).
4. Optionally cap the **max dimension** to shrink huge photos further.
5. Compare the before/after file size live, then click **Download compressed image**.

> Tip: For photos, choose **JPEG** or **WebP** — they compress far better than PNG. PNG is lossless and best kept for screenshots, logos, or text/graphics with sharp edges.

## How it works
- Loads the image into an off-screen `<canvas>`.
- Re-encodes it via `canvas.toBlob()` at the chosen quality/format (JPEG, WebP, or PNG), optionally resizing first.
- Everything happens locally in your browser — nothing is ever uploaded anywhere.

## Deploying / self-hosting
This is a static site — deploy it anywhere that serves static files (Hostinger, Netlify, Vercel, GitHub Pages, S3, etc.):
1. Upload `index.html`, `robots.txt`, and `sitemap.xml` to your web host's public/root folder.
2. Domain is already set to `image.trucirkl.com` in `index.html`, `robots.txt`, and `sitemap.xml`.
3. (Optional) Add an `og-image.png` (1200×630) at the site root for nicer social-media link previews.

## Files
- `index.html` — the entire app (HTML/CSS/JS, no build step, no dependencies).
- `robots.txt` / `sitemap.xml` — SEO files for search engine indexing (update the domain before deploying).

## License
MIT — free to use, modify, and share.

## Keywords
image compressor, compress image online, reduce image size, photo compressor, JPG compressor, PNG compressor, WebP compressor, resize image online, shrink photo size, free image compression tool, compress image without losing quality, online photo optimizer, reduce photo size for upload, image compressor no upload, private image compressor
