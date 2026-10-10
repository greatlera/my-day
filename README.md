# My Day — PWA

## Publish on GitHub Pages

1. Create a GitHub repository named `my-day` (lowercase, with a hyphen).
2. Upload the contents of this folder to the repository root: `index.html`, `manifest.json`, `service-worker.js`, and `icons/`.
3. In **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
4. Wait until Pages reports that the site is published. The expected URL is `https://greatlera.github.io/my-day/`.
5. Open that URL in Chrome on Android and verify the page loads before installing.
6. If an older version was previously installed from the same URL, uninstall that app and reinstall it after deployment.

The app's calendar data is stored in browser `localStorage`. Avoid clearing site storage unless you have backed up any important data.
