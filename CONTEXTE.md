# Contexte — Site TechWall

## Objectif

Site vitrine pour la chaîne YouTube Techwall d'Aymen (pages Home, À propos, Cours).

## État actuel

- Refonte effectuée avec des données réelles (issues des imports YouTube dans `context/import/`).
- Pages présentes : index (Home), À propos, Cours.
- Miniatures de playlists (18/19, hors Cybersécurité — pas de données de playlist disponibles), miniatures des 4 vidéos "Cours récents" et photos des 3 fondateurs intégrées.

## Étapes clés

- Refonte du site avec données réelles (playlists, vidéos Techwall importées).
- Repo GitHub dédié créé et publié en public via `git subtree split` depuis le monorepo Jarvis : https://github.com/aymensellaouti/techwall-site
- Ajout des miniatures de playlists (depuis `context/import/techwallPlaylistInfos.json`, thumbnails YouTube publiques) et des miniatures vidéo (depuis `context/import/videosTechwall.json`).
- Ajout des photos des 3 fondateurs (fournies par Aymen dans `context/import/`, jamais scrapées automatiquement — refus de scraper LinkedIn sans consentement explicite des personnes concernées).

## Liens

- Repo GitHub : https://github.com/aymensellaouti/techwall-site
- Déploiement live : aucun pour l'instant

## Stack

- HTML statique (`.dc.html`) + `support.js`
- Assets : `assets/logo.jpg`, `assets/team/` (photos fondateurs), `assets/playlists/` (miniatures playlists), `assets/videos/` (miniatures vidéos)
