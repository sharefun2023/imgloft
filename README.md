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
| **SVG → PNG** | Convert SVG vector graphics to high-resolution PNG |
| **Compress PNG** | Reduce PNG file size with quality control |
| **Compress JPG** | Shrink JPEG files — adjust quality vs size |
| **JPG → WebP** | Convert JPEG to Google's modern WebP format |
| **Resize Image** | Change dimensions, constrain proportions |
| **Crop Image** | Interactive crop with preset aspect ratios |

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

# Or run locally
git clone https://github.com/sharefun2023/imgloft.git
cd imgloft
python3 -m http.server 8080 --directory public
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
