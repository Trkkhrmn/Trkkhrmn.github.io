# trkkhrmn.github.io

Personal portfolio website for Tarık Kahraman.

## Deploy to GitHub Pages

1. **Create a GitHub repo** named exactly `trkkhrmn.github.io`

2. **Push this folder:**
   ```bash
   cd trkkhrmn.github.io
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/Trkkhrmn/trkkhrmn.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to repo **Settings** > **Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / **root**
   - Click **Save**

4. Your site will be live at **https://trkkhrmn.github.io** within a few minutes.

## Structure

```
├── index.html    # Single-page portfolio (all sections)
├── style.css     # Dark theme styling
└── README.md     # This file
```

## Customization

- Edit `index.html` to update content (projects, experience, etc.)
- Edit `style.css` to change colors (modify CSS variables at the top)
- Add project screenshots/images as needed
