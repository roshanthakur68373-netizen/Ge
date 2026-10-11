# Nuosic Android music player starter

A mobile-first React + Vite + Capacitor Android project with YouTube video embeds and the requested plan UI:
- ₹29 / 3 months
- ₹49 / 6 months
- ₹99 / 1 year
- ₹199 / lifetime

## Build a debug APK for free (phone-friendly)
1. Create a GitHub repository named `nuosic`.
2. Upload all files in this ZIP to the repository root.
3. Open the repository's **Actions** tab.
4. Choose **Build Nuosic Android APK** and press **Run workflow** (or push to `main`).
5. Open the completed workflow run, scroll to **Artifacts**, and download `nuosic-android-debug-apk`. Extract the APK from the downloaded ZIP and install it on Android.

## Important limitations
- This starter uses embedded YouTube videos. It does not unlock YouTube Music Premium or guarantee audio playback when the screen is off. YouTube's official embedded player and platform policies limit background playback and ad-free behavior; do not attempt to bypass those restrictions.
- Search opens YouTube search results. A production app needs a compliant search/API integration and a backend.
- The displayed subscription prices are UI only. Payment is not wired up. Add FamGateway/FamAPI using a PHP backend, verify payment server-side, and store entitlements in a database. Never put merchant secrets in the APK.
- Lifetime plan should be explicitly defined in terms of what service remains available; hosting/API costs may continue.
- This is a buildable starter source project, not a signed Play Store release APK. The GitHub Actions workflow creates a debug APK. A release requires signing credentials.
