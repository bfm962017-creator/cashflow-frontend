# Cashflow frontend

Plain static site: index.html + config.js. No build step.
Edit config.js and set CASHFLOW_API_URL to your backend URL.
Deploy as a Render Static Site (publish directory: .).

Installable as an app (PWA): manifest.webmanifest + sw.js + icons/. On Android/desktop Chrome use the
"Install app" button (or browser menu > Install). On iPhone open in Safari > Share > Add to Home Screen.
When you change the app shell files, bump CACHE in sw.js so old caches are cleared.
