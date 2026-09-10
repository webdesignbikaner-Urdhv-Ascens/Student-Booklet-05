# Booklet 05 - Think, Stay Safe & Get Future-Ready — Booklet CDN Package

- **Booklet ID:** `student-05`
- **Version:** `1.0.0`
- **Total Pages:** `32`
- **Format:** WebP
- **Target Deployment:** Cloudflare Pages (Custom Domain / *.pages.dev)

## Directory Structure
- `/pages/`: Full resolution zero-padded WebP assets (`0001.webp` to `0032.webp`)
- `/thumbnails/`: Optimized low-bandwidth grid thumbnails (width: 240px, quality: 70)
- `/preview/cover.webp`: High-resolution booklet cover preview
- `/manifest.json`: Deterministic booklet contract consumed by ŪRDHV ASCENS Viewer
- `/_headers`: Cloudflare Edge caching rules (immutable page caching, CORS policy)

## Deployment Instructions
1. Push this directory contents to the dedicated GitHub repository.
2. Link the repository to Cloudflare Pages.
3. Build command: None (Static deploy).
4. Build output directory: `/` (Root).
