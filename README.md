# Keychain Studio — Laser SVG Designer

A free, browser-based keychain layout tool designed for GitHub Pages and mobile editing.

## Publish on GitHub using your phone

1. Sign in to GitHub and create a new repository named `keychain-designer`.
2. Set the repository to **Public** (for free GitHub Pages on the usual GitHub Free setup).
3. Open the repository and tap **Add file → Upload files**.
4. Upload `index.html` from this package and commit the change.
5. Go to **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch `main` and folder `/ (root)`, then save.
8. Wait a minute or two. Your site will be published at:
   `https://YOUR-USERNAME.github.io/keychain-designer/`
   Replace `YOUR-USERNAME` with your GitHub username.

You can edit the website on your phone: open `index.html` in the repository, tap the pencil/edit icon, make changes, then commit them.

## Features
- Default 45 × 30 mm rounded rectangle
- Adjustable dimensions, corner radius, chain hole and position
- Text, font family, size, position, rotation, bold and letter spacing
- Optional image/logo upload
- Multiple-piece sheet preview and SVG sheet export
- Save project to JSON and reopen JSON projects
- Responsive layout for phone and desktop

## LightBurn notes
- SVG dimensions are written in millimetres.
- The rounded outer border and chain hole are vector paths/shapes; text remains SVG text, so font availability can affect its appearance. For reliable results, use a font installed on the computer running LightBurn or convert text to paths in a vector editor before importing.
- Raster logo images are embedded in the SVG, but some laser workflows work better with a clean SVG logo or a separately processed bitmap.
- Import the SVG into LightBurn, check the overall width/height, assign appropriate layers, and frame the job before firing the laser.
- The thickness field is a project note only; it does not change the SVG geometry.
- This is a design helper, not a laser controller. Always use appropriate eye protection, ventilation, fire precautions, and material-safe settings.
