# Tessella

Colour by number and pixel art, in your browser. Open it at [tessella.nahuelgenchi.com](https://tessella.nahuelgenchi.com).

A tessella is one small tile of a mosaic. In Tessella every pixel is one: pick a picture, fill in its numbered tiles, and watch it appear. You can also draw your own on a blank grid.

Its mascots are Tessa, a tortoise whose shell is a mosaic, and Pip, a small round bird. Each comes in sixty styles, and you pick one in Settings: it becomes the logo in the header and the icon on the browser tab. On a phone, pick first and then add Tessella to your Home Screen, and your pick becomes the app icon.

## Your own packs

You can open a zip of pictures you already have, such as an asset pack. Tessella sorts it into sections by its folders, reads names from any page inside the zip, and can dress itself in the pack's colours.

The zip never leaves your computer. Tessella reads it in your browser and keeps it there, so nothing is uploaded and nobody else can see it. That also means your packs and art stay on the device and browser where you made them.

## How it is built

Tessella is one HTML file with no build step and no server code. Cloudflare serves it as static files, as set in `wrangler.jsonc`. To try it locally, serve the folder and open it:

```bash
python3 -m http.server 4173
```
