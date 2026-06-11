# 🏎️ RoGames — Jeu de voiture multijoueur

Jeu de voiture 3D à la troisième personne, jouable dans le navigateur, où tous les joueurs se voient en temps réel. Un hub central donne accès à 5 mini-jeux, et une boutique permet de dépenser des pièces gagnées en jouant.

## Stack technique

| Composant | Technologie |
|---|---|
| Moteur 3D | Three.js (CDN) |
| Physique voiture | Physique arcade custom |
| Multijoueur | Firebase Realtime Database + Auth anonyme |
| Sauvegarde joueur | Firebase (pièces, skins, missions) |
| Hébergement | GitHub Pages |
| Portail / vitrine | Site Notion `rogames.notion.site` |

## Jouer

Ouvrir `index.html` dans un navigateur, ou visiter la version en ligne (GitHub Pages).

**Contrôles** : `Z`/`↑` accélérer · `S`/`↓` freiner/reculer · `Q`/`D` ou `←`/`→` tourner · `Espace` drift · `R` respawn

## Phases de réalisation

- [x] **Phase 1 — Cœur du jeu** : voiture 3e personne, physique arcade, hub 3D, caméra, rendu HD
- [ ] **Phase 2 — Multijoueur** : Firebase (auth anonyme, sync positions, présence, pseudos)
- [ ] **Phase 3 — Mini-jeux** : les 5 modes avec portails, scores et récompenses
- [ ] **Phase 4 — Économie** : pièces, boutique, skins, missions quotidiennes, sauvegarde
- [ ] **Phase 5 — Déploiement** : mise en ligne GitHub Pages
