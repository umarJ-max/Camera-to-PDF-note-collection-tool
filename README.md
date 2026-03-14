# SnapNotes 📷→📄

Scan handwritten notes with your phone camera and download them as a single PDF. Works 100% in the browser — no server, no uploads, completely private.

## Features
- Mobile-first design (built for one-hand phone use)
- Back camera by default with front-camera flip button
- Swipeable thumbnail strip while shooting
- Touch drag-to-reorder pages in review screen
- Rotate individual photos
- A4 / Letter / A5 · Portrait / Landscape
- Custom filename
- Haptic feedback on capture (supported phones)
- Space bar shortcut on desktop

---

## Deploy: GitHub → Vercel (Free, ~3 minutes)

### Step 1 — Create a GitHub Repo
1. Go to [github.com](https://github.com) → **New repository**
2. Name it e.g. `snapnotes`
3. Leave it public (Vercel free tier works with public repos)
4. Click **Create repository**

### Step 2 — Upload Files
On the new repo page click **uploading an existing file**, then drag in:
- `index.html`
- `vercel.json`
- `README.md`

Click **Commit changes**.

### Step 3 — Deploy on Vercel
1. Go to [vercel.com](https://vercel.com) → Sign up free (use your GitHub account)
2. Click **Add New → Project**
3. Select your `snapnotes` repo → Click **Deploy**
4. Done! You'll get a free URL like `snapnotes-abc.vercel.app`

Every time you push changes to GitHub, Vercel auto-redeploys.

---

## Local Test (Optional)
Just open `index.html` in Chrome/Edge on your phone or PC.  
> Note: camera requires HTTPS in production — Vercel handles this automatically.

## Files
| File | Purpose |
|------|---------|
| `index.html` | The entire app (single file) |
| `vercel.json` | Vercel routing config |
| `README.md` | This file |