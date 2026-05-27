# Xteink wallpaper maker

### 👉 [View the web app](https://xawk64.github.io/Xteinkx4x3-Wallpaper-Maker/) 🖼️

Small static web app to crop and resize images for Xteink e-readers, with a device-shaped preview. Supports **X4 480×800 / 800×480** and **X3 528×792 / 792×528**. Export is **24-bit uncompressed BMP** only. Everything runs in the browser; no images are uploaded to any server.

## Usage

1. Open `index.html` in a modern browser (double-click, or use a local / hosted URL).
2. Add images, adjust fit, scale, pan (sliders or drag on the preview), and optional grayscale + dither.
3. Click **Download BMP** and copy the file to your device.

## Repository layout

| File         | Role                               |
| ------------ | ----------------------------------- |
| `index.html` | Page structure                        |
| `style.css`  | Layout and UI                         |
| `app.js`     | Canvas compositing and BMP encoder    |

## License

MIT — see [LICENSE](./LICENSE).
