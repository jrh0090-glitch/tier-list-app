# Tier List App — PWA

Rate anything with a customizable S/A/B/C/D/F tier list.
Import list packs (.json files) or build your own.

---

## Deploy to GitHub Pages

### Step 1 — Create a repository

1. Go to **github.com** and sign in
2. Click the **+** in the top right → **"New repository"**
3. Name it anything — e.g. `tier-list-app`
4. Set it to **Public** (required for free GitHub Pages)
5. Leave everything else as-is and click **"Create repository"**

### Step 2 — Upload the files

1. On the new repo page, click **"uploading an existing file"**
2. Open your unzipped `tier-list-pwa` folder
3. Select **all files and the icons folder** — drag them into the GitHub upload area
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `list-cheesecake-factory.json`
   - `list-jenis-ice-cream.json`
   - `list-pizza-toppings.json`
   - `list-TEMPLATE.json`
   - The entire `icons/` folder
4. Scroll down and click **"Commit changes"**

> **Important:** Upload the files *inside* the folder directly — not the folder itself.
> GitHub needs `index.html` at the root of the repo, not inside a subfolder.

### Step 3 — Enable GitHub Pages

1. Go to your repo's **Settings** tab
2. In the left sidebar, click **Pages**
3. Under **"Build and deployment" → Source**, select **"Deploy from a branch"**
4. Under **Branch**, select **main** and **/ (root)**, then click **Save**
5. Wait about 60 seconds, then refresh the page

Your app is live at:
**`https://YOUR-USERNAME.github.io/tier-list-app`**

GitHub will show the URL at the top of the Pages settings once it's ready.

---

## How users install it

### iPhone / iPad
> Safari only — Chrome on iOS cannot install PWAs

1. Open the app URL in **Safari**
2. Tap the **Share button** (box with arrow at the bottom)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **"Add"**
5. App icon appears on the home screen — opens full-screen, no browser bar

### Android
1. Open the app URL in **Chrome**
2. Chrome shows a banner: **"Add Tier List to Home screen"** — tap it
   - Or: tap the three-dot menu → **"Install app"**
3. Done — app appears in your app drawer

### Desktop (Chrome / Edge)
- A small install icon appears in the address bar — click it
- App opens in its own window without browser chrome

---

## Updating the app

To push an update:
1. Make your changes to `index.html` (or any other file)
2. Go to your GitHub repo
3. Click the file → click the pencil icon to edit, or drag a new version onto the repo
4. Commit the change

Users get the update automatically the next time they open the app.

---

## Creating and sharing list packs

Edit `list-TEMPLATE.json` in any text editor:

```json
{
  "name": "My List Name",
  "emoji": "⭐",
  "subtitle": "A short description",
  "items": [
    "Item One",
    "Item Two",
    "Item Three"
  ]
}
```

Save it as `list-whatever.json` and either:
- **Import it** into the app via the "+ Import" button
- **Upload it** to your GitHub repo so others can download and import it too

---

## Included list packs

| File | Contents |
|------|----------|
| `list-cheesecake-factory.json` | All 34 Cheesecake Factory cheesecake flavors |
| `list-jenis-ice-cream.json` | 31 Jeni's Splendid Ice Cream flavors |
| `list-pizza-toppings.json` | 40 pizza toppings |
| `list-TEMPLATE.json` | Blank template for your own lists |
