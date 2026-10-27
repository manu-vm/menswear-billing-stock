MENSWEAR BILLING & STOCK — OFFLINE VERSION

Files:
- index.html
- manifest.webmanifest
- service-worker.js

Offline features:
- App shell is cached after the first successful visit over HTTPS.
- Product stock, saved bills, and settings are stored in this browser's localStorage.
- Bills can be prepared and saved offline after the app has been opened online once.
- PDF generation uses the browser print dialog; offline support depends on the browser's print/save-PDF capability.

Important:
- This version is OFFLINE-capable, but does NOT yet sync data to Firebase or another cloud.
- Data is stored per browser/device. Clearing browser data may erase it.
- Back up from Settings regularly.
- For PWA offline caching, host on HTTPS (Firebase Hosting, Netlify, etc.) and open it once online. Then use Add to Home Screen.
- If the app is used on multiple devices, their data will NOT sync until cloud sync is implemented.
- Verify GST rates and legal invoice requirements before official use.
