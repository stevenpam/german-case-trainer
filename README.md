# German Case Trainer

A Progressive Web App for learning German grammatical cases. Works offline once installed.

## Files

- `index.html` — the app (self-contained, no build step needed)
- `manifest.json` — PWA metadata
- `sw.js` — service worker for offline caching
- `icon.svg` — home screen icon

## Setup on GitHub Pages

1. Go to github.com and create a new **public** repository (e.g. `german-case-trainer`)
2. Upload all four files to the repository root
3. Go to **Settings → Pages**
4. Under "Source", select **Deploy from a branch**, choose **main**, folder **/ (root)**
5. Click Save — GitHub will show you the URL (e.g. `https://yourusername.github.io/german-case-trainer`)

## Install on iPhone

1. Open the URL in **Safari** or **Chrome** on your iPhone
2. Tap the **Share** button (box with arrow)
3. Tap **Add to Home Screen**
4. Tap **Add**

The app will appear on your home screen like a native app. After the first load it works completely offline.

## Data

Your quiz stats are saved in the browser's localStorage, so they persist between sessions on the same device.
