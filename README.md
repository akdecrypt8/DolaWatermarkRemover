# Dola.com Watermark Remover

Userscript that removes image watermarks on **Dola / Doubao** (`dola.com`, `doubao.com`) chat by swapping proxied image URLs (`~tplv-*`) with the original raw image URLs, then auto-downloads the images.

## Features

- Intercepts image URLs across `fetch`, `XMLHttpRequest`, `WebSocket`, `<img>`, `<source>`, `srcset`, CSS `background-image`, and anchor clicks
- Full SPA navigation support (History API / turbolinks hooks)
- Auto-downloads detected images in batches, with queue controls
- Floating `IMG` button + quick panel to scan, pause, clear queue, toggle options

## Install

- Install a userscript manager such as [Tampermonkey](https://www.tampermonkey.net/) or [Violentmonkey](https://violentmonkey.github.io/)
- Install this script and open `https://www.dola.com/chat`

## Usage

- `Ctrl+Shift+D` scan the current page
- `Ctrl+Shift+P` toggle the control panel
- Click the floating `IMG` button to scan / open the panel

## License

GPL-3.0-or-later
