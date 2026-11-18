# Flexi – work-time tracker (iPhone web app)

All your data stays on your phone. No login, works offline.

## One-time setup (about 15 minutes)

1. Create a free account at https://github.com (on a computer is easiest).
2. Click **+ → New repository**. Name it `flexi`, choose **Private** or **Public**, click **Create repository**.
   (GitHub Pages on a private repository needs a paid plan. Choose Public if you're on the free plan:
   only the app code is public, never your hours – those stay on your phone.)
3. On the new repository page click **uploading an existing file**, then drag in **everything from this folder**
   (index.html, sw.js, manifest.webmanifest and the icons and lib folders). Click **Commit changes**.
4. Go to **Settings → Pages**. Under *Branch* choose `main` and `/ (root)`, click **Save**.
5. After a minute the page shows your address, like `https://yourname.github.io/flexi/`.

## Put it on your iPhone

1. Open that address in Chrome (or Safari).
2. Tap **Share → Add to Home Screen**.
3. Open Flexi from the Home Screen icon. Go to **Settings** and enter your name, ID and department.

## Good habits

- Tap **Back up** when the app reminds you, and save the file to iCloud Drive or OneDrive.
- New phone: install the app the same way, then **Settings → Restore from backup**.
- At month end: **Export → Export & close month**, then send the PDF + Excel to accounting.

## Updating the app

Replace the changed files in the GitHub repository and change `VERSION` in `sw.js`
(e.g. `flexi-2`). Open the app twice to pick up the new version. Your data is not affected.
