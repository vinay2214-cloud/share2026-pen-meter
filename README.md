# Connected Pen-Meter: interactive 3D concept

This is a static website: `index.html` plus three script files in `vendor/`. It needs no build step and no server.

- **Offline:** double-click `index.html`.
- **QR code:** the QR code in the deck points to `https://vinay2214-cloud.github.io/share2026-pen-meter/`.

## Publish on GitHub Pages (matches the QR code)

1. Create a **public** repository named exactly `share2026-pen-meter`.
2. Upload the contents of this folder, so that `index.html` sits at the repository root.
3. Turn on Pages: **Settings → Pages → Deploy from a branch**, then select `main` and `/ (root)`.
4. After 1–2 minutes, open the URL and scan the QR code with two different phones.

## Publish on Render (alternative)

1. Create a new **Static Site** and connect it to the repository.
2. Leave the build command empty. Set the publish directory to `.`.
3. Render gives the site a different address, so regenerate the QR code for that address.

The site collects no data. Its URL options are used to make still images:

- `?still=1` shows the 3D model only.
- `&view=exploded` opens the exploded view.
- `&lens=1` turns on the surveillance lens.
- `&marks=dots` shows numbered dots only.

three.js r147 is included under the MIT licence (see `vendor/THREE_LICENSE.txt`).
