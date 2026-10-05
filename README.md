# Gym Sous-Sol — suivi de musculation

Application autonome dans un seul fichier (`index.html`), sans dépendance externe : elle fonctionne hors-ligne.

## Programme (prise de masse, barre + banc + haltères) — 2 séances alternées
| Séance A — Poussée / Bas du corps | Séries × réps | Repos |
|---|---|---|
| Développé couché à la barre | 4 × 6-8 | 2 min |
| Goblet Squat ou Squat barre | 4 × 8-10 | 2 min |
| Fentes arrière (haltères) | 3 × 10 / jambe | 1 min 30 |
| Élévations latérales (haltères) | 3 × 12-15 | 1 min 30 |

| Séance B — Tirage / Chaîne postérieure | Séries × réps | Repos |
|---|---|---|
| Soulevé de terre jambes tendues à la barre (RDL) | 4 × 8-10 | 2 min |
| Rowing buste penché à la barre | 4 × 8-10 | 2 min |
| Développé militaire debout | 3 × 8-10 | 1 min 30 |
| Curls biceps | 3 × 10-12 | 1 min 30 |

## Mon matériel
- **Barre et disques en livres** : barre vide de 20 lb. Pour les exercices à la barre, on entre le **poids total** et l'app affiche les disques à mettre **de chaque côté** (ex. 115 lb → 47,5 lb / côté).
- **Haltères en kilos** : on entre le poids **d'un haltère**.
- Réglable dans Réglages → Mon matériel, et par exercice (Barre / Haltères).

## Installer comme une app sur le téléphone
1. Activer GitHub Pages : Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
2. Ouvrir https://thomas-simard.github.io/Gym/ **avec du réseau**.
3. iPhone (Safari) : Partager → « Sur l'écran d'accueil ». Android (Chrome) : menu ⋮ → « Installer l'application ».
4. L'app s'ouvre ensuite en plein écran, avec son icône, même sans réseau.

## Exporter / importer l'historique
Onglet **Historique** (ou Réglages) → « Exporter l'historique » crée un fichier `gym-historique-AAAA-MM-JJ.json`. « Importer un fichier d'historique » le recharge (remplace les données actuelles). Il existe aussi une version copier/coller en texte.

## Utilisation
- Ouvrir https://thomas-simard.github.io/Gym/ sur le téléphone (une fois GitHub Pages activé), puis « Ajouter à l'écran d'accueil ». Après une première ouverture avec réseau, l'app est gardée en cache (`sw.js`) et s'ouvre sans réseau.
- **Séance** : choisir A ou B (la prochaine est mise en avant). Poids et réps sont pré-remplis avec la dernière séance ; cocher ✓ puis « Lancer le repos ».
- **Minuteur** : −30 s / +30 s / Reset ; bip, vibration (Android) et flash vert à zéro.
- **Historique** : séances passées + records (1RM estimé, formule d'Epley).
- **Programme** : modifier exercices, séries, réps et temps de repos.
- **Réglages** : matériel (unités, poids de la barre), son, repos automatique, sauvegarde (fichier ou copier-coller).

Les données sont stockées dans le `localStorage` du navigateur : faire une sauvegarde de temps en temps.

## Crédits
Photos des exercices : [free-exercise-db](https://github.com/yuhonas/free-exercise-db) (domaine public, Unlicense), intégrées directement dans `index.html`.
