# DUOR — E-commerce site

Static export, ready to host on GitHub Pages.

## Deploy
1. Push this folder's contents to a GitHub repo (root or /docs).
2. In repo Settings → Pages, set the source to that branch/folder.
3. Done — index.html loads support.js (page runtime) and image-slot.js (product images) from the same folder, and pulls React/Babel from a CDN at runtime. No build step required.

Do not rename or move support.js, image-slot.js, or .image-slots.state.json relative to index.html — they are loaded by relative path.
