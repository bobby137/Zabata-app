# ZABATA Android wrapper (Capacitor)

Requirements: Node 20+, Android Studio (includes the Android SDK and JDK 17+).

    npm install
    npx cap add android
    npx cap sync android
    npx cap open android      # opens Android Studio

Test APK: Android Studio > Build > Build APK(s)
  -> android/app/build/outputs/apk/debug/app-debug.apk

After editing www/index.html, run `npx cap sync android` again.
