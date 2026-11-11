# Nibbly homepage

Landing page and privacy policy for the Nibbly game. The site is static HTML, CSS, and JavaScript, using artwork and copy from the game project.

## Build

Run `node build.mjs`. This copies the homepage into `dist/` and generates `dist/privacy.html` from `privacy.json`. The game images are in `dist/assets/`.

## Vercel

Import this repository into Vercel with the repository root as the project root. `vercel.json` sets the build command and `dist` output directory. No environment variables or package installation are required.

The Google Play button is a coming-soon placeholder. Add the store URL to `index.html` after release. Review `privacy.json` against the released game's data practices before making the site public or using the policy URL in a store listing.
