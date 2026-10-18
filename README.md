# MKNO 2.0 — APK de test

Projet Android hors ligne (interface, bibliothèque mécanique, diagnostic guidé, garage). Le Bluetooth ELM327 est volontairement exclu de cette version.

## Compilation GitHub Actions
1. Créer un dépôt GitHub séparé ou une branche de test pour éviter d’écraser MKNO 1.0.
2. Envoyer **le contenu de ce dossier** à la racine du dépôt, y compris `.github/workflows/android-apk.yml`.
3. Ouvrir l’onglet Actions > Build MKNO test APK > Run workflow (ou pousser sur main).
4. Après succès, ouvrir l’exécution > Artifacts > MKNO-2.0-test-debug et télécharger l’archive contenant `app-debug.apk`.
5. Installer le fichier APK sur Android. Son identifiant d’application est `com.mkno.app.interface2` pour conserver MKNO 1.0.

Attention : compilation non vérifiée dans cet environnement ; vérifier les résultats sur GitHub. L’APK de debug n’est pas une version Play Store. Ne pas utiliser les données de diagnostic comme seule base pour une intervention dangereuse.
