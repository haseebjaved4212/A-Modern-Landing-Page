# Landing Page Project

Project: Simple static landing page showcasing a product/brand using local fonts and images.

## Repository root contents

- `index.html` - The main landing page HTML file.
- `style.css` - Styles for the landing page.
- `script.js` - Small JavaScript for interactivity (if any).
- `raybanlogo.png` - A logo image used by the page.
- `IMG_7564.JPG`, `IMG_7565.JPG`, `IMG_7566.JPG`, `IMG_7567.JPG`, `IMG_7568.JPG` - Example images used in the design.

## Purpose

This is a minimal static landing page project intended to demonstrate a lightweight, locally-hosted design with custom fonts and images. It can be used as a template for simple product or portfolio landing pages.

## Getting started (Windows)

1. Clone or copy the project folder to your machine.
2. Open the folder in your code editor (e.g., Visual Studio Code).
3. Serve the site locally (recommended) or open `index.html` directly in your browser.

## Options to open

- Double-click `index.html` to open in your default browser. Note: Some font and script features may fail when opened via the `file://` protocol depending on the browser's local file security policies.

## Project structure and important files

- `index.html`

  - Contains the page structure, references local fonts in `Founders_Grotesk/`, links to `style.css` and `script.js`.
  - Make sure paths reflect the folder structure if you move files.

- `style.css`

  - Contains CSS including `@font-face` rules. If fonts are not loading, check the font paths and ensure the MIME types are supported by your server.

- `script.js`
  - Holds any small DOM interactions (e.g., mobile nav toggle). If the file is empty, nothing is required for the page to function.

- **Fonts**

This project bundles the Founders Grotesk font family in the `Founders_Grotesk/` folders. The fonts are OpenType (`.otf`) files.

- If you plan to deploy to a web server, convert or provide `woff`/`woff2` files for improved performance and broader browser compatibility.
- Ensure you have the correct licensing for web use before deploying the fonts publicly.

- **Images**

Images are included at the project root. Optimize images before production — use tools like `squoosh`, `imagemin`, or other compressors.

## Common tasks

- Add a new page - create a new `.html` file and update navigation.
- Change fonts - update `@font-face` in `style.css` or replace the fonts in `Founders_Grotesk/`.
- Deploy - upload the project to any static hosting (Netlify, GitHub Pages, Firebase Hosting, Vercel, S3).

## Edge cases and notes

- Opening using `file://` may block local fonts/scripts in some browsers. Serve via HTTP for best results.
- If fonts don't load after deployment, verify server MIME types and that the font files are not blocked by CORS.
- On slow networks, large images and uncompressed fonts will slow page loads. Convert fonts to `woff2` and compress images for production.

## Testing

- Visual check: open in major browsers (Chrome, Edge, Firefox, Safari) and compare rendering.
- Mobile responsiveness: resize the window and test on an actual device if available.

## Accessibility tips

- Add meaningful `alt` text to all images used for content conveyance.
- Ensure sufficient color contrast for text and interactive controls.
- Use semantic HTML and proper heading order in `index.html`.

## Suggestions and next steps

- Convert fonts to `woff2` and add `font-display: swap` to `@font-face` rules.
- Optimize images and add responsive `srcset`/`picture` elements.
- Add basic SEO meta tags and Open Graph metadata to `index.html`.
- Add a minimal `package.json` and npm scripts for local tooling if you plan to add build steps.

## License & copyright

- This repository contains font files and images; ensure you have rights to redistribute them.

## Contact

If you want further help expanding this landing page (animations, form handling, or deploying), tell me what you'd like next and I can implement it.
