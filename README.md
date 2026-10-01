<p align="center">
  <h1 align="center">imgloft</h1>
  <p align="center"><strong>Free Image Tools — Convert, Compress, Resize, Crop. All in Your Browser.</strong></p>
  <p align="center">
    <a href="https://imgloft.com"><strong>imgloft.com</strong></a>
  </p>
</p>

---

A collection of free, client-side image tools. No upload, no signup, no watermark — everything happens in your browser.

## Tools

| Tool | What It Does |
|------|-------------|
| **[SVG → PNG](https://imgloft.com/svg-to-png)** | Convert SVG vector graphics to PNG at the exact pixel size you ask for |
| **[Compress PNG](https://imgloft.com/compress-png)** | Re-encode a PNG and strip metadata — PNG is lossless, so there is no quality slider |
| **[Compress JPG](https://imgloft.com/compress-jpg)** | Shrink JPEG files with a real quality slider (0.1–1.0) |
| **[JPG → WebP](https://imgloft.com/jpg-to-webp)** | Convert JPEG to WebP at a quality you pick — much smaller files |
| **[Resize Image](https://imgloft.com/resize-image)** | Set an exact pixel width and height, or pick one of four presets |
| **[Crop Image](https://imgloft.com/image-crop)** | Interactive crop with preset aspect ratios |

Each page documents its own limits rather than hiding them: PNG has no quality setting (the format is lossless), resizing has no percentage mode, the resizer always writes PNG whatever you drop in, and the cropper's output is always a PNG too. If a tool can't do something, the page says so.

## Why Client-Side?

Every online image tool that uploads your files to a server has three problems:

1. **Privacy** — your images sit on a stranger's server
2. **Speed** — round-trip upload + process + download is slow
3. **Limits** — file size caps, daily quotas, forced signup

imgloft processes everything in your browser using Canvas API and Web Workers. Zero bytes leave your device.

## Quick Start

```bash
# No install — just open
open https://imgloft.com

# Or run locally (plain HTML, no build step, no dependencies)
git clone https://github.com/sharefun2023/imgloft.git
cd imgloft
python3 -m http.server 8080
# → http://localhost:8080
```

## Tech Stack

- HTML5 Canvas API for image manipulation
- Web Workers for non-blocking processing
- Vanilla JavaScript, zero frameworks
- Cloudflare Pages (global edge hosting)

## License

MIT

## Links

- **Live**: [imgloft.com](https://imgloft.com)
- **More tools**: [sqlformat.io](https://sqlformat.io) | [23232322.xyz](https://23232322.xyz) | [pagetext.io](https://pagetext.io)
