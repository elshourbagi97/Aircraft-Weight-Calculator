Aircraft Weight Calculator — PWA package

Files:
- index.html: the calculator
- manifest.webmanifest: install/app metadata
- service-worker.js: offline cache
- icons/: app icons

INSTALL / HOSTING:
1. Upload the contents of this folder to a static HTTPS host (for example GitHub Pages).
2. Open the published HTTPS address on the phone while online.
3. Android: Chrome menu > Install app (or Add to Home screen).
4. iPhone: Safari Share > Add to Home Screen.
5. Open the installed app once while online so the offline cache is populated.
6. Test by turning on Airplane Mode and opening the installed app.

Important:
- PWA installation and service workers require HTTPS (localhost is the development exception).
- Do not open index.html directly from a file manager if you want PWA installation/offline caching.
- Aircraft weights marked unavailable in the supplied sheet remain unavailable in the calculator.
