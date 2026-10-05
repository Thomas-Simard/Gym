# Gym Sous-Sol — suivi de musculation

Application autonome dans un seul fichier (`index.html`), sans dépendance externe : elle fonctionne hors-ligne.

## Programme (prise de masse, haltères) — 2 séances alternées
| Séance A — Poussée / Bas du corps | Séries × réps | Repos |
|---|---|---|
| Goblet Squat | 4 × 8-10 | 2 min |
| Développé couché ou incliné | 4 × 8-10 | 2 min |
| Fentes arrière | 3 × 10 / jambe | 1 min 30 |
| Élévations latérales | 3 × 12-15 | 1 min 30 |

| Séance B — Tirage / Chaîne postérieure | Séries × réps | Repos |
|---|---|---|
| Soulevé de terre jambes tendues (RDL) | 4 × 8-10 | 2 min |
| Rowing à un bras | 4 × 8-10 | 2 min |
| Développé militaire debout | 3 × 8-10 | 1 min 30 |
| Curls biceps | 3 × 10-12 | 1 min 30 |

## Utilisation
- Ouvrir https://thomas-simard.github.io/Gym/ sur le téléphone (une fois GitHub Pages activé), puis « Ajouter à l'écran d'accueil ». Après une première ouverture avec réseau, l'app est gardée en cache (`sw.js`) et s'ouvre sans réseau.
- **Séance** : choisir A ou B (la prochaine est mise en avant). Poids et réps sont pré-remplis avec la dernière séance ; cocher ✓ puis « Lancer le repos ».
- **Minuteur** : −30 s / +30 s / Reset ; bip, vibration (Android) et flash vert à zéro.
- **Historique** : séances passées + records (1RM estimé, formule d'Epley).
- **Programme** : modifier exercices, séries, réps et temps de repos.
- **Réglages** : kg/lb, son, repos automatique, sauvegarde (fichier ou copier-coller).

Les données sont stockées dans le `localStorage` du navigateur : faire une sauvegarde de temps en temps.

## Crédits
Photos des exercices : [free-exercise-db](https://github.com/yuhonas/free-exercise-db) (domaine public, Unlicense), intégrées directement dans `index.html`.
