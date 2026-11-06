# Cadence – installer l’app sur votre iPhone

Une PWA doit être hébergée en ligne (en https) pour s’installer. GitHub Pages est gratuit.

## 1. Mettre les fichiers en ligne (une seule fois, ~5 min)
1. Créez un compte sur https://github.com (gratuit).
2. Cliquez sur **New repository**, nommez-le `cadence`, cochez **Public**, puis **Create repository**.
3. Cliquez sur **uploading an existing file** et glissez TOUS les fichiers de ce dossier
   (index.html, sw.js, manifest.webmanifest et les 3 images .png). Validez avec **Commit changes**.
4. Allez dans **Settings → Pages**. Dans « Branch », choisissez `main` puis **Save**.
5. Après une minute, votre app est disponible à l’adresse :
   `https://VOTRE-PSEUDO.github.io/cadence/`

Cela marche aussi depuis l’iPhone dans Safari (en « version ordinateur »), mais c’est plus confortable sur un ordinateur.

## 2. Installer sur l’iPhone
1. Ouvrez l’adresse ci-dessus dans **Safari**.
2. Touchez **Partager** (carré avec une flèche) → **Sur l’écran d’accueil** → **Ajouter**.
3. Lancez Cadence depuis son icône : plein écran, et fonctionne ensuite sans connexion.

## Mettre à jour l’app
1. Sur GitHub, ouvrez votre dépôt puis **Add file → Upload files**.
2. Glissez les nouveaux fichiers : ils remplacent les anciens. Validez avec **Commit changes**.
3. Ouvrez Cadence sur l’iPhone : après quelques secondes, un bandeau
   « Une nouvelle version de Cadence est prête » apparaît. Touchez **Mettre à jour**.

Pour vos prochaines modifications : changez toujours le numéro dans sw.js
(`cadence-v2` → `cadence-v3`…), sinon l’app ne détecte pas la mise à jour.

## Bon à savoir
- Laissez l’app ouverte à l’écran pendant la séance : iOS met en pause les apps web en arrière-plan
  (le minuteur se recale tout seul au retour, mais les sons ne sonnent pas pendant ce temps).
- Si vous n’entendez rien, vérifiez le bouton silencieux de l’iPhone.
- Vos données restent sur le téléphone. Pensez à « Réglages → Exporter » de temps en temps.
