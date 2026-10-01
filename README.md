# MKNO Android

Version Android native de l'application web MKNO fournie dans `index.html`.

## Ce qui est inclus
- Application Android native utilisant WebView.
- Interface MKNO conservée telle quelle.
- Fonctionnement hors ligne : le contenu est embarqué dans l'APK.
- `localStorage` activé pour conserver les données de l'application.
- Bouton Retour Android géré.
- Icône MKNO extraite du manifest fourni.

## Générer l'APK
1. Installer Android Studio.
2. Ouvrir ce dossier `MKNO-Android`.
3. Laisser Android Studio synchroniser Gradle.
4. `Build > Build APK(s)`.
5. L'APK debug sera généré dans `app/build/outputs/apk/debug/`.

Pour le Play Store, il faudra ensuite créer une signature de production et un paquet AAB.
