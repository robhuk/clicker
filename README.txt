XC TALLY COUNTER — PWA PACKAGE

Files:
- index.html: responsive passenger tally counter
- manifest.webmanifest: unique PWA identity (xc-tally-counter)
- sw.js: offline cache/service worker
- icon-192.png and icon-512.png: app icons

Install:
1. Upload the contents of this folder to a static HTTPS host (keep files together).
2. Open the hosted URL in Chrome on Android or Safari on iOS.
3. Android: browser menu > Install app / Add to Home screen.
   iPhone/iPad: Share > Add to Home Screen.
4. Open the installed app. After the first successful load, core files are cached for offline use.

Capacity logic:
- First Class capacity: 26 seats.
- Standard Class: 186 on 4-car, 246 on 5-car.
- FULL AND STANDING appears when either class count EXCEEDS its seating capacity.
- Counts are in-memory for the current app session; use Copy summary before resetting or closing if you need a record.


Unique installation identity:
- PWA manifest ID: ./?app=xc-tally-counter-rh-20261012
- Service worker cache: xc-tally-counter-rh-20261012-v1
These distinguish this app from other PWAs when hosted at a distinct path/origin.
