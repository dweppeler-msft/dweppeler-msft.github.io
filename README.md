# Daniel Weppeler — CV Website

A lightweight, responsive single-page CV built with plain HTML & CSS — ready for GitHub Pages.

## Files
- `index.html` — content and structure
- `styles.css` — styling (light/dark theme, print-friendly)

## Preview locally
Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Deploy to GitHub Pages
1. Create a new repository on GitHub (e.g. `cv` or `danielweppeler.github.io`).
2. Push these files to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Add CV website"
   git branch -M main
   git remote add origin https://github.com/<your-user>/<repo>.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`, pick `main` / `/ (root)`, and save.
5. Your site goes live at `https://<your-user>.github.io/<repo>/`
   (or `https://<your-user>.github.io/` if the repo is named `<your-user>.github.io`).

## Notes
- Toggle light/dark mode with the button in the top-right (preference is saved).
- Use the browser's **Print → Save as PDF** for a clean printable copy.
- Update the hobbies in `index.html` (search for "Hobbies & Interests") to match your real interests.
