# CraveWise Android releases

This public repository hosts official compiled CraveWise Android releases. Application source is maintained separately in a private repository. Only signed APKs, release notes and update metadata belong here.

Download the APK from the [latest GitHub Release](https://github.com/Valtern/Cravewise-Releases/releases/latest) and install it manually once. Subsequent releases are detected in CraveWise Settings. `latest.json` is the public updater manifest and includes the numeric Android build code, exact APK URL and SHA-256 checksum.

If you installed 0.2.0, manually install 0.2.1 or later once to enable reliable update checks.

Android may ask you to allow installation from your browser or from CraveWise, and to confirm the system installer. Updates are not silent. Official updates keep the same application ID and signing certificate and use an increasing versionCode. Older debug-signed development builds require uninstalling that build before the first official installation; this clears local app data, while account preferences remain on the service.

APK installation is Android-only. No Google Play or paid distribution service is required. Never upload signing keys, credentials, customer data or private source here.