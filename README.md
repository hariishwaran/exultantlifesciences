# Exultant Lifesciences Website

Static site — a single `index.html` plus an `assets/images` folder with every
image the page uses (logo, hero background, About section photo, WhatsApp
icon, and all 19 product photos).

## Folder structure

```
exultant-website/
├── index.html
└── assets/
    └── images/
        ├── logo.png
        ├── hero-bg.jpg
        ├── about-product-range.png
        ├── whatsapp-icon.png
        └── products/
            ├── biliant-m.jpg
            ├── exulmag-s.jpg
            └── ... (one file per product)
```

## Uploading to GitHub

1. Create a new repository on GitHub (don't initialize it with a README).
2. In a terminal, `cd` into this `exultant-website` folder and run:

   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```

3. To host it for free with GitHub Pages: go to the repo's **Settings → Pages**,
   set the source to the `main` branch, and save. Your site will be live at
   `https://<your-username>.github.io/<your-repo>/` within a minute or two.

## Notes

- All image paths in `index.html` are relative (e.g. `assets/images/logo.png`), so the folder works as-is once uploaded — no edits needed.
- The two "Coftant-D Syrup" and three "Esowall-40" product images are different pack photos of those products; their files are suffixed `-2` / `-3` to keep filenames unique.
