Simplotel Frontend Assignment (HTML + CSS Only)

This project recreates the provided two-page PDF design using only semantic HTML and modern CSS. It is responsive across desktop, tablet, and mobile, and remains intact from 50% to 200% zoom.

Project Structure
- index.html
- styles/styles.css
- images/
  - hero-desktop.svg
  - hero-mobile.svg
  - gallery-1.svg
  - gallery-2.svg
  - gallery-3.svg
  - gallery-4.svg
  - logo.svg
  - icon-hamburger.svg
  - icon-arrow.svg

Replace the placeholder images in `images/` with the assets from the PDF package. Keep names or update paths in `index.html`.

How to Run Locally
- Double-click `index.html`, or
- Serve with a simple HTTP server:
  - Python 3: `python -m http.server 8000` then open http://localhost:8000

Deploy to GitHub Pages
1. Push this folder to a GitHub repo on the `main` branch.
2. Settings → Pages → Deploy from a branch → `main` /root.
3. Wait for the URL to appear.

What to Customize
- Colors: edit variables in `styles/styles.css` under `:root`.
- Images: replace files in `images/` or update paths.
- Fonts: replace the Google Font import and `--font-sans`.

QA Checklist
- Matches PDF at 320, 768, 1024, 1280px widths.
- Works from 50%–200% zoom without breaking.
- Images keep aspect ratio; not stretched or pixelated.
- Mobile nav via hamburger; keyboard accessible.
- Text doesn’t overflow; buttons ≥44px height.
- No frameworks or JS libraries used.



