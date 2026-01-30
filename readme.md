# iPad Inventory & Sales Tracker (LocalStorage)

This is a single‑file web app for tracking products and sales. It stores data **only on the device** using the browser's `localStorage` (no server, no SharePoint).

## What’s new in this build
- **JSON Backup**: Export all data + config to a `.json` file.
- **JSON Restore**: Import that file later (replaces local data).
- **Home Screen Icon**: Black square with white **UD** letters for iPad/iPhone.

## Publish on GitHub Pages
1. Create a new public repo (e.g., `ipad-inventory`).
2. Upload the contents of this ZIP to the repo root.
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose branch `main`, folder `/ (root)`, then **Save**.
6. Wait ~1 minute, then open: `https://<your-username>.github.io/ipad-inventory/`.

## Install on iPad (Home Screen)
1. Open your GitHub Pages URL in **Safari** on iPad.
2. Tap the **Share** button.
3. Tap **Add to Home Screen**.
4. Name it (e.g., “Inventory”). The custom **UD** icon will be used.

## Backup & Restore
- Go to **Settings → Backup & Restore**.
- **Export JSON** downloads a file like `inventory-backup-YYYY-MM-DD-HH-MM.json`.
- **Import JSON** selects a previously exported file and **replaces** local data on this device.

## Notes
- All data persists **only on this device** and browser profile (localStorage).
- Clearing Safari website data will erase the records.
- Works offline after the first load.

## Optional next steps
- Turn into a full PWA (service worker) for better offline caching.
