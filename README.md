# Jalon

Suivi de projets simple : un seul fichier HTML, hors ligne, données stockées sur l'appareil (IndexedDB).

- **Tableau de bord** filtrable (statut, service, chef de projet, priorité, météo) : retards, avancement vs temps écoulé, budget consommé et projeté, charge en jours-homme, jalons à 30 jours, tâches bloquées, risques critiques, points d'attention.
- **Météo automatique** par projet (vert / orange / rouge) avec la liste des raisons, forçable à la main.
- **Planning Gantt** : avancement, jalons (clés, atteints, en retard), date de fin initiale pour voir les glissements, tâches dépliables.
- **Risques** : matrice probabilité × impact 4 × 4, plans d'action.
- **Équipe** : personnes par service, disponibilité, charge sur 4 semaines.
- **Point hebdo** : revue guidée projet par projet, quelques minutes par semaine.
- **Rapport direction** imprimable / PDF, synthèse copiable pour un mail, export CSV.

Déploiement : pousser `index.html` sur un dépôt GitHub et activer GitHub Pages.
Les données ne quittent pas le navigateur : utiliser Réglages → Exporter / Importer pour passer d'un appareil à l'autre.
