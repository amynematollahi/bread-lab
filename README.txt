BREAD LAB - FREE PRIVATE IPHONE WEB APP

To install on iPhone, the folder must first be published as a static HTTPS website.
One free route: create a public GitHub repository and upload index.html, app.js, sw.js, manifest.webmanifest, icon-192.png, icon-512.png to the root. In repository Settings > Pages, choose Deploy from a branch, main, / (root), and Save. Once the site is available at https://YOURNAME.github.io/REPO/, open it in Safari on iPhone, tap Share > Add to Home Screen > Add.

IMPORTANT PRIVACY: A public GitHub repository exposes the app SOURCE CODE, not your locally stored bake records. Do not upload personal records or JSON backups to the repository. The app uses localStorage on the device and does not send bake data to a server. Local storage can be deleted when Safari site data is cleared. Export JSON regularly and save to Files/iCloud Drive. If you switch browsers, devices, or URLs, import your JSON backup.

To update the app, replace the files in the repository and increase the CACHE value in sw.js to refresh offline assets.
