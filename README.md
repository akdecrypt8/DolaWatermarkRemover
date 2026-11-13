# Dola.com Watermark Remover

Userscript that removes image watermarks on **Dola / Doubao** (`dola.com`, `doubao.com`) chat by swapping proxied image URLs (`~tplv-*`) with the original raw image URLs, then auto-downloads the images.

## Features

- Intercepts image URLs across `fetch`, `XMLHttpRequest`, `WebSocket`, `<img>`, `<source>`, `srcset`, CSS `background-image`, and anchor clicks
- Full SPA navigation support (History API / turbolinks hooks)
- Auto-downloads detected images in batches, with queue controls
- No custom UI. Runs silently on top of the official Dola web experience

## Install

- Install a userscript manager such as [Tampermonkey](https://www.tampermonkey.net/) or [Violentmonkey](https://violentmonkey.github.io/)
- Install this script and open `https://www.dola.com/chat`

## Usage

- Images with watermarks are swapped to raw URLs and auto-downloaded

## License

GPL-3.0-or-later
