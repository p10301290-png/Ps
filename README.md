# Power System — GitHub Pages / PWA

## Upload to GitHub Pages
1. Extract this ZIP.
2. Upload **all files and the `icons` folder** to the root of your GitHub repository (same folder as `index.html`).
3. Commit the changes. In **Settings → Pages**, select your deployment branch/folder if Pages is not already enabled.
4. Open the published HTTPS URL in Chrome on Android.

## Install like an app
1. Open the GitHub Pages website in Chrome.
2. Open the browser menu (⋮).
3. Choose **Install app** or **Add to Home screen** (wording varies).
4. Launch Power System from the home screen. It is configured for standalone display and includes a service worker for offline loading.

## Important
- This is a **PWA package**, not a compiled native APK. It can install and run in an app-like standalone window. To make a real APK, wrap the published PWA with a trusted Android PWA/TWA builder or build an Android WebView app.
- App data is stored locally in the browser on that device. Use the app's Backup/Restore option before clearing browser/site data or changing devices.
- The app uses Google Fonts when online; if unavailable, system fallback fonts are used.


Single-icon upload package: `icon.png` is in the repository root. Upload `index.html`, `manifest.webmanifest`, `sw.js`, and `icon.png` together to the repository root. `README.md` is optional.
