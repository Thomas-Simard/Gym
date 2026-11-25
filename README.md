# Gym Sous-Sol — suivi de musculation

Application autonome dans un seul fichier (`index.html`), sans dépendance externe : elle fonctionne hors-ligne.

## Programme (prise de masse) — 2 séances alternées, exercices polyarticulaires uniquement
Une seule installation de barre par séance (jamais de changement de hauteur en cours de séance) ; le reste aux haltères.

| Séance A — Squat barre + haltères | Séries × réps | Repos |
|---|---|---|
| Squat à la barre (barre haute) | 4 × 6-8 | 2 min |
| Développé incliné aux haltères | 4 × 8-10 | 2 min |
| Rowing à un bras (haltère) | 4 × 8-10 / bras | 2 min |
| Fentes arrière (haltères) | 3 × 10 / jambe | 1 min 30 |

| Séance B — Développé couché barre + haltères | Séries × réps | Repos |
|---|---|---|
| Développé couché à la barre (barre basse) | 4 × 6-8 | 2 min |
| Soulevé de terre jambes tendues aux haltères (RDL) | 4 × 8-10 | 2 min |
| Développé militaire debout (haltères) | 3 × 8-10 | 1 min 30 |
| Rowing buste penché aux haltères | 3 × 8-10 | 1 min 30 |

## Mon matériel
- **Disques de la barre en kilos**, **barre vide de 20 lb** (≈ 9,07 kg). Pour les exercices à la barre, on entre les disques **d'un seul côté** ; l'app calcule le total (2 × côté + barre).
- **Haltères en kilos** : on entre le poids **d'un haltère**.
- **kg ou lb au choix** : sur chaque exercice, le bouton kg | lb change l'unité de saisie ; l'équivalent dans l'autre unité s'affiche sous chaque case. Le choix est mémorisé par exercice.
- Réglable dans Réglages → Mon matériel (unité des disques, poids et unité de la barre vide, unité des haltères).

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
