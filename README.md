# Noa เรียนสนุก

Petit jeu d'apprentissage pour les enfants de l'école primaire thaïe (อนุบาล 3 à ป.6) : maths, thaï, sciences, le monde, logique, français, anglais, code couleur des résistances, programmation, électricité, musique, santé et sécurité, mesures et cadrans d'aviation, drapeaux et pays. Les questions sont en thaï, avec une traduction française.

**Jouer :** https://chtipilot.github.io/NOA/

## Nouveautés de la version 3.0

- **Au démarrage**, le jeu demande l'appareil utilisé (téléphone, tablette ou ordinateur) pour savoir si l'enfant écrit avec le doigt ou avec la souris. Modifiable dans l'espace parents.
- **ฝึกเขียน · Écrire** : tracer des consonnes thaïes, des chiffres thaïs et arabes, puis des lettres latines, au doigt ou à la souris (3 niveaux : pointillés, lettre pâle, de mémoire).
- **Bouton « ? »** sur chaque question : une explication de méthode en thaï, lue à voix haute, comme un maître ou une maîtresse. Elle s'ouvre aussi après une erreur.
- **6 nouvelles matières** : programmation (grilles, boucles, bugs, binaire), électricité (circuits animés, conducteurs, loi d'Ohm), musique (sons générés, portée, instruments thaïs), santé et sécurité, mesures (règle, balance, thermomètre, pichet) avec **cadrans d'avion** (anémomètre, altimètre, horizon artificiel, compas, variomètre, compte-tours, jauge), drapeaux et capitales.
- **Défis « ⭐ ท้าทาย »** au-delà du programme quand l'enfant est très à l'aise.
- Sur ordinateur : réponses au clavier (1 à 4, Entrée, ?) et certains calculs à taper.
- Toutes les illustrations sont dessinées dans le jeu (SVG animés) : pas d'image externe, le jeu reste un seul fichier.

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
