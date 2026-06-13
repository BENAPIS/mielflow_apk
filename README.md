# 🐝 MielFlow APK (Benapi Lab)

Ce dépôt public est le **canal de distribution et de contrôle** officiel de l'application MielFlow. 

Il fonctionne en binôme avec le cœur du projet (le code source Dart/Flutter), qui reste hébergé dans un dépôt privé pour des raisons de sécurité et de protection des clés API.

---

## 🔗 Le lien entre les deux projets

L'architecture est interconnectée de la manière suivante :

1. **Développement (Dépôt Privé `benapis_lab`)** : C'est là que le code de l'application et le nouveau modèle gaussien de miellée sont développés et compilés.
2. **Distribution (Ce Dépôt Public `mielflow_apk`)** : Reçoit les fichiers d'installation `.apk` prêts à l'emploi dans la section **Releases**.
3. **Contrôle à distance (Fichier `config.json`)** : L'application installée sur le téléphone interroge en arrière-plan le fichier `config.json` présent ici à chaque démarrage pour vérifier s'il faut forcer une mise à jour automatique.

---

## 📲 Installer ou mettre à jour l'application

1. Rendez-vous dans la section **[Releases](https://github.com/BENAPIS/mielflow_apk/releases)** (à droite sur écran d'ordinateur, ou en bas sur mobile).
2. Téléchargez le dernier fichier `.apk` disponible.
3. Ouvrez le fichier sur votre appareil Android pour lancer l'installation (autorisez les sources inconnues si votre navigateur le demande).
4. Vos données et l'historique de vos ruches seront automatiquement conservés lors de la mise à jour.
