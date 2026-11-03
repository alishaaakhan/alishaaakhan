# Setup & Customization

## Publish as your profile README
1. On GitHub, create a **public** repository named exactly `alishaaakhan` (same as your username).
2. Upload everything in this folder (`README.md`, `LICENSE`, `assets/`) to the repository root, keeping the folder structure.
3. Open https://github.com/alishaaakhan - the README renders above your pinned repositories.
No build step, npm or framework is needed.

## Customize
- **Text** - edit `README.md` (About, experience table, links).
- **Cards and dashboards** - open the matching file in `assets/` in any text editor; text is plain `<text>` elements.
- **Project links** - the three project cards link to your profile. When a repository is public, change the `<a href>` around that card in `README.md`.
- **Colors** - gradients are defined at the top of each SVG (`#acc` is the blue/violet accent).
- **Portraits** - replace `assets/pointing-portrait.png` with another transparent PNG of similar proportions. The ID card embeds a cropped copy of the first portrait inside `assets/digital-id-card.svg` (GitHub blocks external files inside images), so to change it, re-embed a base64 PNG in the `<image>` element.

## Notes
- Animations use SVG/SMIL, which GitHub displays when images are shown via `<img>`. Every SVG shows a complete static layout if animation is not supported.
- SVG fonts are system fonts with fallbacks, so text looks slightly different per device.
- The pointing portrait and the ID-card portrait are your personal photos and are not covered by the MIT license.
