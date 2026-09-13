# Lions Immobilier — Android

Application Android basée sur React + Capacitor.

## Compilation APK

1. Installer Node.js et Android Studio.
2. Dans ce dossier : `npm install`
3. `npx cap add android`
4. `npm run build`
5. `npx cap sync android`
6. `cd android && ./gradlew assembleDebug` (Windows : `gradlew.bat assembleDebug`)

APK debug : `android/app/build/outputs/apk/debug/app-debug.apk`

Pour une version Play Store, créer une clé de signature dans Android Studio puis générer un APK/AAB signé.
