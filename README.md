# Daniel Weppeler — CV Website

A lightweight, responsive single-page CV built with plain HTML & CSS, hosted on GitHub Pages.

🔗 **Live site:** https://dweppeler-msft.github.io/

## Features
- Responsive layout with a navy sidebar and clean typography
- Light / dark mode toggle (remembers your preference)
- Profile photo and a personal "off the keyboard" band
- Compact, print-friendly PDF export (fits ~2 pages)

## Project structure
```
.
├── index.html        # Content and structure
├── styles.css        # Styling (light/dark theme, print layout)
├── profile.jpg       # Header headshot
└── hobby-trail.jpg   # Personal band photo
```

## Preview locally
Open `index.html` directly in a browser, or serve it:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Deploy
The site auto-deploys via GitHub Pages from the `main` branch. To publish updates:

```bash
git add .
git commit -m "Update CV"
git push origin main
```

Pages is configured under **Settings → Pages** (Source: `Deploy from a branch`, branch `main`, folder `/root`).

## Tips
- Toggle light/dark mode with the button in the top-right corner.
- Export a PDF via the **Download as PDF** button (enable *Background graphics* in the print dialog to keep the sidebar colors).
- Swap the photos by replacing `profile.jpg` and `hobby-trail.jpg` (keep the same filenames).

