# DALZON CITY

**Prototype 3D jouable — Android et Web**

DALZON CITY est un jeu original en monde ouvert, avec caméra à la troisième personne, déplacements tactiles, ville générée en 3D et véhicules conduisibles.

## Jouer

Ouvrir le site publié en HTTPS avec Chrome sur Android. Utiliser les boutons tactiles à l'écran : flèches pour se déplacer, **MONTER EN VOITURE** près d'un véhicule, puis accélérer et tourner.

Sur ordinateur : touches **W/A/S/D** ou flèches ; **E** pour entrer ou sortir d'une voiture.

## Publier avec GitHub Pages

1. Ouvrir **Settings → Pages** dans ce dépôt.
2. Choisir **Deploy from a branch**.
3. Sélectionner la branche **main** et le dossier **/(root)**, puis enregistrer.
4. Attendre la fin du déploiement et ouvrir l'adresse HTTPS affichée par GitHub Pages.
5. Sur Android, ouvrir cette adresse dans Chrome puis choisir **Installer l'application** dans le menu.

## Notes techniques

- Application web progressive (PWA) avec manifeste et service worker.
- Rendu 3D avec Three.js chargé depuis jsDelivr ; une connexion Internet est donc nécessaire pour télécharger la bibliothèque au premier chargement.
- Le service worker met en cache les fichiers de l'application, mais la bibliothèque 3D externe peut nécessiter Internet.
- Il s'agit d'une première base de développement, pas d'un jeu AAA comparable à GTA VI. Les missions, sauvegardes, personnages avancés, sons et optimisation graphique restent à développer.
