# Suivi Santé

Application de suivi d'analyses biochimiques avec graphiques. Une valeur qui dépasse sa limite de plus de 20 % passe en rouge (seuil réglable).

Créée par Kamel Nasralli.

## Fichiers à déposer

Déposez ces cinq fichiers à la racine du dépôt :

- `index.html` : l'application
- `manifest.json` : nom et icône de l'application installée
- `sw.js` : permet d'ouvrir l'application sans connexion
- `icon-192.png` et `icon-512.png` : l'icône

## Publier sur GitHub Pages

1. Sur github.com, cliquez sur **New repository**. Donnez-lui un nom, par exemple `suivi-sante`.
2. Cliquez sur **uploading an existing file**, sélectionnez les cinq fichiers, puis **Commit changes**.
3. Ouvrez **Settings**, puis **Pages**.
4. Sous **Build and deployment**, choisissez **Deploy from a branch**, la branche `main` et le dossier `/ (root)`, puis **Save**.
5. Attendez une minute. L'adresse apparaît en haut de la page Pages : `https://VOTRE-NOM.github.io/suivi-sante/`.

## Mettre l'icône sur l'écran d'accueil

Ouvrez l'adresse GitHub Pages (pas le lien claude.ai), puis :

- **Android (Chrome)** : menu ⋮, puis **Installer l'application** ou **Ajouter à l'écran d'accueil**.
- **iPhone et iPad (Safari)** : bouton Partager, puis **Sur l'écran d'accueil**.

L'application s'ouvre ensuite en plein écran, comme une application, et fonctionne aussi sans connexion.

## Confidentialité

`index.html` contient vos résultats d'analyses. Avec un compte GitHub gratuit, un site GitHub Pages est public : toute personne qui connaît l'adresse peut les voir.

- Pour un usage privé, utilisez un dépôt privé avec une offre GitHub qui autorise Pages sur les dépôts privés (Pro, Team ou Enterprise).
- Les mesures ajoutées avec le formulaire restent dans le navigateur de la personne qui les saisit. Elles ne sont pas envoyées à GitHub.

## Sauvegarde

Les mesures ajoutées sont enregistrées dans le navigateur (localStorage). Utilisez l'onglet **Import / Export** pour les sauvegarder en CSV ou JSON avant de vider les données du navigateur ou de changer d'appareil.
