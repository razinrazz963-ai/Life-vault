# LifeVault PWA

## Deploy
1. Upload the contents of this folder to a GitHub repository (keep `index.html`, `manifest.json`, `sw.js`, and `icon.svg` at the repository root).
2. Import the repository into Vercel.
3. For a plain static HTML project, leave the framework preset as Other and use `./` as the output directory (or leave the default if Vercel detects it).
4. Deploy, then open the HTTPS URL in Chrome on Android and choose Install app / Add to Home screen.

## Important data note
This app stores its data in the browser's localStorage on each device. It does not currently sync data between phone and computer. Export a backup from Settings before changing devices or clearing browser data.

## Notifications
The current reminder notifications are checked while the app is open. Push notifications when the app is closed require a push service/backend and are not included in this static PWA package.
