# Lalith Adithya — Portfolio Website

A professional static portfolio website for **Lalith Adithya**, Technical Writer.

- **Live demo (GitHub Pages):** `https://<your-username>.github.io/adithya_portfolio/`

---

## Project Structure

```
adithya_portfolio/
├── index.html                      # Main portfolio page
├── articles/
│   ├── swiggy_article.md           # Swiggy Mobile App User Manual
│   ├── level_l1.md                 # Level 1 Support Knowledge Manual for MS Outlook
│   └── how_to_install_ms_office.md # How to Install Microsoft Office
├── assets/
│   ├── style.css                   # All styles
│   ├── resume.jpg                  # Resume preview image
│   ├── Lalith_TechnicalWriter.pdf  # Downloadable resume PDF
│   └── images/
│       ├── outlook/                # MS Outlook article screenshots
│       ├── ms-office/              # MS Office article screenshots
│       └── swiggy/                 # Swiggy article screenshots (add later)
└── README.md
```

---

## Preview Locally

Choose any one of the methods below. Always run the command from **inside** the `adithya_portfolio/` folder.

### Method 1 — Python (recommended, no install needed)

```bash
cd adithya_portfolio
python3 -m http.server 8000
```

Open your browser and go to: `http://localhost:8000`

### Method 2 — Node.js (`npx serve`)

```bash
cd adithya_portfolio
npx serve .
```

Open your browser at the URL shown in the terminal (usually `http://localhost:3000`).

### Method 3 — VS Code Live Server

1. Install the **Live Server** extension in VS Code.
2. Open `index.html`.
3. Click **Go Live** in the bottom status bar.

---

## Deploy to GitHub Pages

### Step 1 — Create a GitHub repository

```bash
git init
git add .
git commit -m "Initial commit: Lalith Adithya portfolio"
```

### Step 2 — Push to GitHub

```bash
git remote add origin https://github.com/<your-username>/adithya_portfolio.git
git branch -M main
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your repository on GitHub.
2. Click **Settings** → **Pages**.
3. Under **Source**, select `main` branch and `/ (root)` folder.
4. Click **Save**.

Your site will be live at:
```
https://<your-username>.github.io/adithya_portfolio/
```

> It may take a minute or two for GitHub Pages to publish after the first deploy.

---

## Updating the Site

After making changes, push them to GitHub:

```bash
git add .
git commit -m "Update: <describe your change>"
git push
```

GitHub Pages will automatically rebuild and publish the updated site.

---

## Add New Articles (Future)

Use this process whenever you want to add a new article page.

1. Create a new article file inside `articles/`, for example:
   - `articles/my-new-article.md`
2. Add a new article card in `index.html` inside the `#articles` section:
   - Title
   - Short description
   - Link to your new article file
3. If the article needs images, create a folder in:
   - `assets/images/<article-name>/`
4. Add your screenshots/images into that folder.
5. Reference images in your article like:
   - `../assets/images/<article-name>/<image-file-name>`
6. Verify locally:
   - `python3 -m http.server 8000`
   - Open `http://localhost:8000`

### Example for Swiggy article images

- Folder: `assets/images/swiggy/`
- Article file: `articles/swiggy_article.md`
- Example image reference in Markdown:
  - `../assets/images/swiggy/01-home.png`

---

## Tech Stack

- HTML5
- CSS3 (custom, no frameworks)
- Vanilla JavaScript
- Google Fonts (Inter)
