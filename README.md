# Gym Sous-Sol — suivi de musculation

Application autonome dans un seul fichier (`index.html`), sans dépendance externe : elle fonctionne 100 % hors-ligne.

## Utilisation
- Ouvrir https://thomas-simard.github.io/Gym/ sur le téléphone (une fois GitHub Pages activé), puis « Ajouter à l’écran d’accueil ». Après la première ouverture, l’app fonctionne sans réseau tant qu’elle reste en cache ; le fichier `index.html` peut aussi être ouvert directement.
- **Séance** : choisir le jour (le prochain est suggéré), saisir charge et réps, cocher ✓ → minuteur de repos automatique.
- **Historique** : séances passées + records (1RM estimé, formule d'Epley).
- **Programme** : modifier exercices, séries, réps.
- **Réglages** : lb/kg, temps de repos, export/import JSON.

Les données sont stockées dans le `localStorage` du navigateur : exporter régulièrement une sauvegarde.
