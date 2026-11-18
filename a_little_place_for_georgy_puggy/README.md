# A Little Place for Georgy Puggy 😝❤️

A responsive static love-note website with one note unlocking per calendar day and an archive of previous notes.

## Preview
Extract the ZIP and open `index.html` in a browser. For local development, VS Code Live Server is recommended.

## Add her pictures
Put image files in `photos/`, then edit the `photo` path for each note in `messages.js`. The sample paths are `photos/junia-01.jpg` through `photos/junia-14.jpg`. Until you add the pictures, the image area may appear blank.

## Edit messages and dates
Open `messages.js`:
- `LOVE_NOTES_START_DATE` controls the first unlock date (currently 2026-11-18).
- Each item in `LOVE_NOTES` is one day's note, in order.
- Add more objects to continue the series. Older unlocked notes remain available.

The site uses the visitor's device date. It is static: notes and photo paths are stored in the website files, not a private database. Anyone with the public link can view it.

## Publish free with GitHub Pages
1. Create a GitHub repository and upload `index.html`, `messages.js`, `README.md`, and the `photos` folder.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. GitHub will provide the public URL after deployment.

You can also deploy the folder with Netlify Drop. Remember to use only photos she is comfortable sharing publicly.
