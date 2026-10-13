LEAN BULK TRACKER — ANDROID PWA SOURCE

Files:
- index.html: the tracker app
- manifest.json: installable web app metadata
- sw.js: offline cache support

IMPORTANT:
This is a Progressive Web App (PWA) source project, not a compiled Android APK.
For the browser's "Install app" / "Add to Home screen" option to appear reliably,
host these files on an HTTPS website. Opening index.html directly from Downloads
lets you test the page, but does not provide the full installable PWA behavior.

Simple install flow after hosting:
1. Open the HTTPS website in Chrome on Android.
2. Tap Chrome menu (⋮).
3. Choose "Install app" or "Add to Home screen".
4. Launch Lean Bulk Tracker from the home screen.

Data is stored locally in that browser/device. Use "Export backup (JSON)" before
clearing browser data or changing devices. Food nutrition values are entered by
the user and should be checked against package labels or a reliable nutrition source.

To package as a native APK, this project needs an Android wrapper/build step (for
example, a trusted PWA-to-Android packaging workflow). No APK has been compiled here.
