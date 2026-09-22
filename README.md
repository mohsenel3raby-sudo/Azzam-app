# AZZAM Android

Android wrapper for https://azzam-stor.web.app/

## Build APK from a phone with GitHub Actions

1. Create a new GitHub repository.
2. Upload the CONTENTS of this folder to the repository root (not the ZIP itself).
3. Open the repository's **Actions** tab.
4. Open **Build AZZAM APK**.
5. Tap **Run workflow**, then **Run workflow** again.
6. Wait for the build to finish with a green check mark.
7. Open that workflow run and download the **AZZAM-APK** artifact.
8. Extract the downloaded ZIP. Inside is **AZZAM-debug.apk**.
9. Install the APK on your Android phone. Android may ask you to allow installation from your browser/files app.

The workflow also runs automatically after pushes to `main` or `master`.

Note: this is a debug-signed APK for direct testing/installation. A Play Store release should use a private release signing key and an AAB/release build.
