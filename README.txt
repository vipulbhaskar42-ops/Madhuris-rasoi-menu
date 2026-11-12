# Madhuri's Rasoi — 3D Digital Flipbook Menu

## What's included
- Responsive book-style digital menu with page navigation and mobile swipe.
- Search and category shortcuts.
- QR generator: after publishing, paste the live URL to create a downloadable QR PNG.
- Original logo photo crop supplied by the user is used as a visual reference image. It is not a vector/transparent logo.

## Important before public launch
1. Confirm all prices marked `Ask` or `Price to confirm` in `app.js`.
2. Check spelling, availability, portion sizes and taxes with the restaurant.
3. Replace the logo reference photo with an original high-resolution transparent logo if available; this project intentionally does not redraw the logo.
4. Test on Android and iPhone before printing the QR.

## Run locally
Open `index.html` in a browser. For best results, use VS Code Live Server.

## Free hosting recommendation
For a restaurant's business menu, use Cloudflare Pages Direct Upload rather than GitHub Pages. GitHub's Pages documentation says it is not intended as free hosting for an online business. Cloudflare Pages supports direct upload of prebuilt static assets.
- Create a free Cloudflare account.
- Open Workers & Pages → Create → Pages → Direct Upload.
- Upload the unzipped project folder (the folder containing `index.html`).
- Deploy and copy the generated `*.pages.dev` URL.
- Open the live menu URL on a second phone to test.
- On the menu site, tap QR Setup, paste the live URL, Generate QR code, then Download QR PNG.

Hosting policies and limits can change. Review the host's current terms before launch.
