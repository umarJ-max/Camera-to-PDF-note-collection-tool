# SnapNotes 📷→📄

Scan handwritten notes with your phone camera and download them as a single PDF. Works 100% in the browser — no server, no uploads, completely private. Installable as a PWA on your home screen.

## Features
- Mobile-first design (built for one-hand phone use)
- Back camera by default with front-camera flip button
- Flashlight / torch toggle for low-light scanning
- Swipeable thumbnail strip while shooting
- Touch drag-to-reorder pages in review screen
- Rotate individual photos
- Full-bleed PDF export — images fill the entire page, zero white borders
- PDF page sized to match each photo's exact dimensions
- Custom filename
- Haptic feedback on capture (supported phones)
- Space bar shortcut on desktop
- Installable PWA — works offline, adds to home screen

---

## Install on Mobile (PWA)
1. Open the site in Chrome (Android) or Safari (iOS)
2. Android: tap the 3-dot menu → **Add to Home Screen**
3. iOS: tap Share → **Add to Home Screen**

---

## Local Test (Optional)
Just open `index.html` in Chrome/Edge on your phone or PC.  
> Note: camera and torch require HTTPS in production — Vercel handles this automatically.

## Files
| File | Purpose |
|------|---------|
| `index.html` | The entire app (single file) |
| `manifest.json` | PWA manifest (icons, name, theme) |
| `sw.js` | Service worker for offline support |
| `vercel.json` | Vercel static config |
| `icons/` | App icons for PWA and home screen |
| `README.md` | This file |
