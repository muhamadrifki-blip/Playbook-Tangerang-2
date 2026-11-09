# Playbook BAE Accurate Online Tangerang 2 — PWA Fix

Upload **all five files** in this folder to the root of the GitHub repository, replacing the existing files:

- `index.html`
- `manifest.webmanifest`
- `service-worker.js`
- `icon-192.png`
- `icon-512.png`

The icon paths in the manifest and service worker intentionally match the root-level icon files shown in the repository. After upload, wait for GitHub Pages deployment.

On Android Chrome, open the site, then use the browser menu and choose **Install app** if available. If Chrome still shows only **Add to Home screen**, check Chrome's site installability diagnostics and ensure the service worker is activated; Chrome may expose installation differently by version/device.
