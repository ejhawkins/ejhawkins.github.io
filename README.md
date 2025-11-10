# Trend Report Hero Demo

This small project adds a simple static `index.html` hero card that mimics the look of the Artlist Trend Report hero (placeholder image with the article URL text).

Files added:

- `index.html` — hero card with a placeholder for the image showing the URL text.
- `serve.js` — tiny Node static server used for quick local testing.
- `package.json` — updated scripts: `start` runs the static server, `open` opens the page in the default browser.

Quick start:

```bash
# install dependencies if needed (none required for the tiny server)
npm start
# open in browser (macOS)
npm run open
```

Then visit http://localhost:3000

Replace the placeholder in `index.html` with an actual `<img src="...">` when you have an image to use.

