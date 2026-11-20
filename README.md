# Noa เรียนสนุก

Petit jeu d'apprentissage pour les enfants de l'école primaire thaïe (อนุบาล 3 à ป.6) : maths, thaï, sciences, le monde, logique, français, anglais et code couleur des résistances. Les questions sont en thaï, avec une traduction française.

**Jouer :** https://chtipilot.github.io/NOA/

## Plusieurs joueurs

- Au premier lancement, chaque enfant crée son profil : prénom, animal, âge et classe.
- Chaque joueur a son propre niveau, qui s'adapte à ses réponses, et ses propres scores.
- Le tableau des scores (🏆) compare les joueurs : étoiles, réussite, plateaux gagnés, niveau estimé.
- L'espace parents (🔒, protégé par une multiplication) affiche le suivi détaillé du joueur choisi, en français et en thaï.

## Où sont les scores ?

Les scores sont enregistrés **dans le navigateur de l'appareil** (stockage local). Rien n'est envoyé sur Internet, et rien n'est stocké dans ce dépôt.

- Pour garder une copie ou changer d'appareil : Espace parents → « Exporter tous les joueurs », puis « Importer une sauvegarde » sur l'autre appareil.
- Les sauvegardes des versions 1.x (fichier `Noa_sauvegarde_….json`) s'importent dans le profil du joueur choisi.

## Fichiers

- `index.html` : tout le jeu, dans un seul fichier, sans dépendance (seule la police Mali vient de Google Fonts).
- `icon.svg`, `icon-*.png`, `apple-touch-icon.png`, `favicon-48.png`, `manifest.json` : l'icône écureuil 🐿️, utilisée par « Ajouter à l'écran d'accueil » sur téléphone.
