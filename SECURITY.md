# Security and privacy notes

- ZaherCyber is an RSS reader and software catalogue; it does not remotely control a device or run downloaded security tools.
- Release binaries are downloaded directly from HTTPS links published by the relevant upstream project. The app never silently installs APK files.
- On Android, APK installation is handed to the Android package installer and requires the user's system permission and confirmation.
- SHA-256 is calculated after download. A publisher checksum is compared only when the official release metadata supplies one; a calculated hash alone is not proof of publisher authenticity.
- Bookmarks, feed cache, preferences, and download-job metadata are stored locally using app storage. No ZaherCyber account or private API key is required.
- The app currently does not translate news/article text; it shows publisher-provided excerpts and links to original pages.
- Always verify project, platform, architecture, license and publisher signatures before installing software. Perform security testing only with explicit authorization.
