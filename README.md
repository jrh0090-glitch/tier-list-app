# Tier List App — PWA

Rate anything with a customizable S/A/B/C/D/F tier list.
Import list packs (.json files) or build your own.

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
