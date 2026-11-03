BODYSHOP TRACKER - MOBILE BOTTOM NAVIGATION FIX

Replace these two files in the ROOT of your GitHub Pages repository:
1. index.html
2. sw.js

Keep your existing manifest.webmanifest, icon files, startup image, and other app assets.
Commit both files to the main branch and wait for the GitHub Pages Deploy job to show a green tick.

This update makes the content area scroll independently while the bottom tab bar remains as a permanent row at the bottom of the mobile app viewport. It also updates the service worker cache version to v5 so older cached app files are cleared when the new worker activates.
