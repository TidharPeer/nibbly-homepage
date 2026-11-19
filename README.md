# Nibbly homepage

Landing page, Terms of Service, and privacy policy for the Nibbly game. The site is static HTML, CSS, and JavaScript, using artwork and copy from the game project.

## Build

Run `node build.mjs`. This copies the homepage and `terms.html` into `dist/` and generates `dist/privacy.html` from `privacy.json`. The game images are in `dist/assets/`.

## Vercel

Import this repository into Vercel with the repository root as the project root. `vercel.json` sets the build command and `dist` output directory. No environment variables or package installation are required.

The App Store and Google Play areas are coming-soon placeholders. Add the store URLs to `index.html` after release. Review `privacy.json` and `terms.html` against the released game's data practices and purchase setup before using their URLs in store listings.
