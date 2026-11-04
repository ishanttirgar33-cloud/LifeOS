LifeOS PWA package

Files:
- index.html: your uploaded LifeOS app
- manifest.webmanifest: installable app metadata
- sw.js: basic offline app-shell cache
- icons/: 192px and 512px 
app icons

Important:
1. Host these files on an HTTPS website (for 
example GitHub Pages).
2. Open the hosted website in Chrome on Android and test it.
3. For an APK, use 
PWABuilder with the hosted HTTPS URL and choose the Android package option.
4. Keep the signing key 
safe. Do not share it publicly.

This package does not yet add native Android 
notification support. The current reminder feature still stores reminders in browser storage only.
