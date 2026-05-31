# 🦎 Newt Survey Counter

A Progressive Web App for recording newt survey tally counts in the field. Works offline, saves data between sessions, and can be installed to your Android home screen.

## Features

- Tally counters for Great crested newt, Smooth newt, and Palmate newt
- Male / Female / Juvenile / Unknown breakdown per species
- ID guide with key field features for each species and sex
- Save surveys tagged with site name, pond number, and date
- Export all records as a CSV file
- Works fully offline once installed

---

## Setting up on GitHub Pages (free hosting)

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up for a free account if you don't have one.

### Step 2 — Create a new repository
1. Click the **+** button (top right) → **New repository**
2. Name it `newt-survey` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload the files
1. On the repository page, click **uploading an existing file**
2. Upload all files from this folder, keeping the folder structure:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/icon-192.png`
   - `icons/icon-512.png`
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to the repository **Settings** tab
2. Click **Pages** in the left sidebar
3. Under "Source", select **Deploy from a branch**
4. Choose **main** branch, **/ (root)** folder
5. Click **Save**

After a minute or two, your app will be live at:
`https://YOUR-USERNAME.github.io/newt-survey`

---

## Installing to your Android phone

1. Open Chrome on your Android phone
2. Go to your GitHub Pages URL above
3. Tap the three-dot menu → **Add to Home screen**
4. Tap **Add**

The app now appears on your home screen and works fully offline.

---

## Data

All survey records are stored locally on your device using `localStorage`. They are not sent anywhere. Use the **Export CSV** button in the Records tab to download your data.
