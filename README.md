# Morphing — Anniversaire Clio

Atelier de morphing de visages : transformation continue entre deux photos, calculée entièrement dans le navigateur.

## Fonctions

- Neuf repères par visage (triangulation de Delaunay, interpolation géométrique et fondu des couleurs).
- Recadrage automatique sur le visage, ajustable : glisser le fond, molette pour zoomer, bouton « Centrer sur le visage ».
- Animation automatique : 6 secondes par étape, en va-et-vient.
- Export PNG de l'image hybride.
- Enregistrement vidéo intégré : un aller-retour complet (12 secondes), téléchargé en MP4 par défaut (WebM uniquement si le navigateur ne prend pas l'enregistrement MP4 en charge).

Aucune photo n'est envoyée sur un serveur : tout est traité localement sur votre appareil.

## Activer GitHub Pages

1. Ouvrez les réglages du dépôt, puis la section Pages.
2. Source : Deploy from a branch — Branche : main, Dossier : / (root).
3. Enregistrer. Après quelques minutes, le site est disponible sur :
   https://tiboitaly.github.io/morphing-clio/
