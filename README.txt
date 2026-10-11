DANIEL — TECH EDITION
====================

A mobile-first, installable static web app with a restrained instrument-panel visual style: near-black surfaces, fine technical grid, hard edges and DANIEL cyan highlights. The assessment flow and generated action-plan content are retained.

FILES
- index.html: the assessment app
- logo.png: supplied DANIEL brandmark
- icon-256.png: square home-screen launcher icon
- manifest.webmanifest: install metadata
- sw.js: service worker for app-shell caching

DEPLOY
1. Upload the contents of this folder to a static host such as Netlify, Vercel, or GitHub Pages. Keep all five files together and make index.html the site root.
2. Use the site's HTTPS address on Danny's phone.
3. iPhone: open the site in Safari → Share → Add to Home Screen.
   Android: open the site in Chrome → menu (⋮) → Install app / Add to Home screen.

NOTES
- No account, app database, analytics, or application backend is included.
- React, Babel and Tailwind still load from third-party CDNs, so a first visit needs internet. The service worker caches the local app shell, but offline use is not guaranteed because those external libraries may still be needed.
- Answers remain in the page's current memory session and are not submitted to an app server. Reset or close the page to clear them. A saved or printed PDF is a separate copy on the device.
- The assessment contains legal-information content, not legal advice. Its legal claims should be checked by a qualified family lawyer before anyone relies on the suggested action plan.
