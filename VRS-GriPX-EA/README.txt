VRS Home Screen Icon Package
==============================

Files:
- index-UPDATED.html  = full original HTML code with home-screen icon support added
- index-UPDATED.txt   = same full code in TXT format for easy copy/download
- manifest.webmanifest = Android/Chrome PWA manifest
- vrs-icon-32.png
- vrs-icon-64.png
- vrs-icon-180.png    = iPhone/iPad Apple touch icon
- vrs-icon-192.png    = Android/Chrome PWA icon
- vrs-icon-512.png    = Android/Chrome PWA icon

IMPORTANT:
Keep the HTML, manifest.webmanifest, and PNG files in the same deployed folder.
The HTML references the image filenames with relative paths (./...).

Android Chrome:
- Serve the site over HTTPS (or localhost during development).
- Open the site in Chrome and use "Add to Home screen" / "Install app" when offered.
- Chrome uses manifest.webmanifest and the 192/512 PNG icons.

iPhone:
- Open the site in Safari.
- Share -> Add to Home Screen.
- iOS uses vrs-icon-180.png as the Home Screen icon.

The supplied VRS image is used directly as the app icon artwork and resized to the standard icon sizes.
