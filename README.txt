Bodyshop Tracker – Worker Calendar Update

Files:
- index.html: updated app with four separate worker availability calendars and worker addition boxes at the bottom of the Workers tab.
- sw.js: updated service-worker cache version so browsers can fetch the new app files.

To update your GitHub Pages app:
1. Open your bodyshop-tracker repository.
2. Replace the existing index.html and sw.js in the repository root with these two files.
3. Leave your existing manifest, icons, and other app assets in place.
4. Commit the changes to the main branch and wait for the Pages deployment to complete.
5. Reload the app. If an older version remains visible, close the app tab and reopen the site.

Your existing vehicle and worker records are stored in the browser; this update does not intentionally clear them. Export a backup before replacing the live app as a precaution.
