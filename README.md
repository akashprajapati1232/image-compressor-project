# Image Compressor Pro

Image Compressor Pro is a browser-based image compression tool built as a BCA 5th Semester Minor Project by Team Error 404.

## What this does
- Compress JPG, PNG, JPEG, WEBP, GIF, HEIF/HEIC, ICO, and SVG images entirely client-side (no uploads).
- Crop, resize, and set target file size or quality.
- Preserve privacy — images never leave the user's device.

## Quick start (presentation / demo)
1. Open `index.html` in a modern browser (Chrome, Edge, Firefox or Safari).
2. Upload any supported image or drag & drop into the upload area.
3. Adjust compression settings (Quality / Dimensions / Target Size).
4. (Optional) Click the crop icon on the preview to open the cropper.
5. Click `Compress Image` and then `Download Compressed Image`.

## Files of interest
- `index.html` — Main app (demo-ready landing page)
- `css/styles.css` — Main styling (presentation-ready theme)
- `css/responsive.css` — Responsive rules
- `css/crop.css` — Crop modal styles
- `js/script.js` — Core logic: upload, compress, preview, download
- `js/crop.js` — Cropper.js glue code
- `PROJECT_PRESENTATION_GUIDE.md` — Detailed slide-by-slide guide for presenting the project
- `pages/` — Supporting pages (About, Contact, Privacy, Terms)

## Presentation checklist (for BCA 5th Semester)
- Prepare a short demo image (<= 2 MB) to show live compression.
- Open `index.html` in a browser in full-screen mode for the demo.
- Have `PROJECT_PRESENTATION_GUIDE.md` open for slide notes (it includes a ready slide structure).
- Show: upload → settings → optional crop → compress → download (highlight privacy & performance).
- Mention team members and year (Team Error 404 — BCA 5th Semester, 2025).

## Notes & troubleshooting
- Max file size is 10MB (client-side limit enforced in `js/script.js`).
- HEIF/HEIC support relies on `libheif-js` — may require a modern browser.
- If the download button looks disabled, ensure compression finished and `Download Compressed Image` appears.

## Next steps (suggested)
- Prepare 3-4 slides/screenshots for the presentation (homepage, settings, cropper, before/after).
- Optional: export `PROJECT_PRESENTATION_GUIDE.md` to PDF or copy content into your PPT tool.

Good luck with your presentation — highlight the privacy-first architecture and the browser-only processing!
