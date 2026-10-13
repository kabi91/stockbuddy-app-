STOCKBUDDY PWA — FREE ANDROID INSTALLATION

WHAT IS INCLUDED
- index.html: StockBuddy app
- manifest.webmanifest: app name, display and icons
- sw.js: caches the app shell for offline opening
- icons/: Android app icons

IMPORTANT
The app must be served from an HTTPS website (or localhost for development) for Chrome to offer installation and for the service worker to work. Opening index.html directly from Downloads will not activate PWA installation.

FREE HOSTING OPTION: GITHUB PAGES
1. Sign in or create a free account at https://github.com
2. Create a new public repository named stockbuddy-app.
3. Upload all files and folders from this package, preserving their folder structure.
4. In the repository, open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
6. Wait for GitHub Pages to publish the site. Open the generated https://...github.io/stockbuddy-app/ address in Chrome on Android.
7. In Chrome, open the three-dot menu and tap Install app or Add to Home screen (wording varies).

DATA WARNING
This version stores business records in local browser storage. It does not sync to the cloud. Browser storage may be cleared, and installing the PWA does not automatically transfer existing records from the locally opened file. Export a CSV and JSON backup before switching versions. Test with fictional records until secure cloud backup and user accounts are implemented.

OFFLINE NOTE
The service worker caches the app shell. It does not create cloud sync or protect records against browser data deletion.
