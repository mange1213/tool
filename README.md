# Tool App — New Repository Package

## Publish on GitHub Pages
1. Create a **new public repository** named `tool-app-new` (or another name you prefer).
2. Upload the files from this folder directly into the repository root (not the enclosing folder).
3. In Settings → Pages, select Deploy from a branch, branch `main`, folder `/(root)`, then Save.
4. Wait for the Pages site to publish. The URL will be `https://YOUR-USERNAME.github.io/tool-app-new/`.
5. Open `.../manifest.webmanifest`, `.../icon-192.png`, and `.../sw.js` to verify they load.

## Moving existing data
On the OLD working tablet app, open Backup & Restore and download a complete JSON backup. Keep a second copy somewhere safe. Open the new site, go to Backup / Restore, and import that JSON. Check equipment, workers and active checkouts before relying on it. Do not erase the old app until you have confirmed the new copy contains the correct data.

## Important limits
This is a local-first app: each browser/device has its own records. It does not automatically synchronize the phone and tablet. This package is rebuilt from the original ZIP but is not yet live-tested on your device.
