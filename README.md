# ArchiveLab — GitHub Pages

## Structure

```
/
├── index.html          ← Marketing page
├── support/
│   └── index.html      ← Support URL
├── privacy/
│   └── index.html      ← Privacy Policy
└── assets/
    ├── screen1.png     ← Screenshot: Instagram Space
    ├── screen2.png     ← Screenshot: Canvas
    ├── screen3.png     ← Screenshot: Home / Social Spaces
    └── screen4.png     ← Screenshot: OCR Result / Gallery
```

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g. `archivelab` or your app name)
2. Upload all files maintaining the folder structure above
3. Go to **Settings → Pages → Source → Deploy from branch → main / root**
4. Your site will be live at `https://gentelmandi.github.io/REPO_NAME/`

## App Store URLs to add

In `index.html`, replace the `href="#"` on both store buttons with your real App Store / Google Play URLs once your app is published.

## Screenshots to add

Place your 4 app screenshots into the `assets/` folder:
- `screen1.png` → Social Spaces / Instagram space (image1.png)
- `screen2.png` → Canvas view (image_2.png)
- `screen3.png` → Home screen grid (image3.png)
- `screen4.png` → OCR/Gallery result (image_4.png)

## URLs to use in App Store Connect

| Field | URL |
|---|---|
| Marketing URL | `https://gentelmandi.github.io/REPO_NAME/` |
| Support URL | `https://gentelmandi.github.io/REPO_NAME/support/` |
| Privacy Policy URL | `https://gentelmandi.github.io/REPO_NAME/privacy/` |
