# thoughtnerve.github.io

This repository hosts your public portfolio and homepage at https://thoughtnerve.github.io/.

## How to Manage Your Portfolio

### 1. Updating Your LinkedIn Posts
When you scrape new posts using **LiSaver** and export your portfolio HTML:
1. Copy the exported HTML file into this folder.
2. Rename it to `index.html` to overwrite the existing one.
3. Commit and push the changes:
   ```bash
   git add index.html
   git commit -m "Update portfolio with latest posts"
   git push origin main
   ```

### 2. Adding More Pages
You can add more static pages to this repository (e.g., `about.html`, `projects.html`, `contact.html`):
1. Create the new HTML files in this folder.
2. Link them from your main `index.html` using relative links (e.g., `<a href="about.html">About Me</a>`).
3. Commit and push:
   ```bash
   git add .
   git commit -m "Add new pages"
   git push origin main
   ```

All changes pushed to the `main` branch will automatically build and go live via GitHub Pages.
