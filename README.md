# FitForge — Mobile-friendly PWA starter

## Publish from your Android phone using GitHub Pages
1. Open https://github.com in Chrome and sign in/create an account.
2. Create a **public** repository named `fitforge-workout`.
3. Open the repo → **Add file → Upload files**.
4. Extract this ZIP using your phone's Files app, then upload `index.html`, `manifest.webmanifest`, `sw.js`, and the `icons` folder contents while preserving the `icons/` folder.
5. Commit the upload.
6. Open **Settings → Pages**. Choose **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
7. Wait for the URL shown on the Pages screen, then open it in Chrome.
8. In Chrome's three-dot menu, choose **Install app** or **Add to Home screen** if offered.

## Current limitations
This is a public static prototype/PWA. It has no cloud accounts, synced data, payments, or native Play Store release. Workout history stays in that browser/device. Do not add secret API keys to a public repository.

## Later
After testing the published PWA, consider PWABuilder to explore Android packaging, then review current Google Play developer and policy requirements before submission.
