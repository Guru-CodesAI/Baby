# Pip’s Midnight Nursery 🌙

**A tiny, playful dream world made for Pip** — the curious skull baby and Junior Dream Engineer at the Midnight Nursery.

Explore a gentle, colorful bedtime portfolio with original interactions, little inventions, and a 3D dream workshop. The site is built as a self-contained HTML page, with no application framework or package installation required.

## Step inside

- **Meet Pip:** Get to know the sleepy, sweet dream engineer and the things Pip loves to make.
- **Explore the inventions:** Play a lullaby, light the lantern, and deliver dreams across an illustrated rooftop neighborhood.
- **Make a dream:** Pick a moonbeam, a soft song, or a cloud puff and see your choices appear around a 3D dream-cloud. Mix a dream to make it bounce and celebrate.
- **Find the little surprises:** Follow the story scenes and look for a hidden bedtime wish.
- **Settle in:** Switch between day and night themes and turn sound on or off whenever you like.

The design uses warm cream, berry, lavender, pink, and honey-gold colors, with Fraunces, DM Sans, and Fredoka typography. Animations respect reduced-motion preferences; the dream-cloud can also be activated by keyboard.

## Run it locally

No build step or dependencies are needed.

1. Download or clone this repository.
2. Open [`Pip’s Midnight Nursery.html`](./Pip’s%20Midnight%20Nursery.html) in a modern browser.

The illustrations are embedded in the HTML file. Google Fonts and the Three.js library are loaded from their respective CDNs, so those enhancements need an internet connection. The page’s text and built-in HTML/CSS remain part of the local file.

## Deploy to Vercel

This repository is a static site; Vercel serves the existing HTML directly. The included [`vercel.json`](./vercel.json) sends visits to `/` to the nursery page.

1. Import `Guru-CodesAI/Baby` in [Vercel](https://vercel.com/new).
2. Select **Other** as the framework preset, if prompted.
3. Leave the build command empty; there is no build step.
4. Set the output directory to `.` (the repository root), if Vercel asks for one.
5. Deploy.

After deployment, the Vercel URL opens the nursery at the site root.

## Project files

| File | Purpose |
| --- | --- |
| [`Pip’s Midnight Nursery.html`](./Pip’s%20Midnight%20Nursery.html) | Complete website, styles, interactions, and embedded artwork |
| [`vercel.json`](./vercel.json) | Rewrites the site root to the HTML page |
| [`LICENSE`](./LICENSE) | Repository license |

## Credits

Pip and the character artwork are credited to the [official haX.baby assets](https://hax.baby/baby/assets/). The interactive 3D scenes use [Three.js](https://threejs.org/), distributed under the MIT License. Fonts are served by [Google Fonts](https://fonts.google.com/).

See [`LICENSE`](./LICENSE) for the repository’s licensing terms. Character artwork and third-party resources remain subject to their respective owners’ terms.
