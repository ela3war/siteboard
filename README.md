# SiteBoard (Android)

Project tracker for an MEP and interior finishing contractor: schedule, crew clashes across projects, materials, variations, client invoices, costs and daily site reports. English and Arabic.

- The app is `app/src/main/assets/index.html` inside a WebView. Data is stored on the phone; use Setup → Export backup regularly.
- Every push to `main` builds a signed APK on GitHub Actions and publishes it as a Release (`SiteBoard.apk`).
- Keep `app/siteboard.keystore`: updates only install over the existing app when signed with the same key.
