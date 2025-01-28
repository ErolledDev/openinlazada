
# PWA Installation Instructions

1. Copy all files to your web server's root directory:
   - index.html
   - manifest.json
   - service-worker.js
   - styles.css
   - icon-192x192.png
   - icon-512x512.png
   - splash-screen.png (if uploaded)

2. Make sure your web server:
   - Serves files with correct MIME types
   - Has HTTPS enabled (required for PWA)
   - Returns proper headers for service worker

3. Test your PWA:
   - Open in Chrome/Edge/Firefox
   - Check if install prompt appears
   - Verify offline functionality
   - Test splash screen and loading animation

Note: The install prompt will appear automatically when the PWA installation criteria are met:
- Site is served over HTTPS
- Has a valid manifest.json
- Has a registered service worker
- User has interacted with the site
- Site meets engagement criteria

For debugging:
1. Open Chrome DevTools
2. Go to Application tab
3. Check Manifest and Service Workers sections
