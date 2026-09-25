# Flux de données React

Les contexts partagent état et résultats entre composants sans multiplier les requêtes.
Les hooks encapsulent chargement, rafraîchissement et transformation des séries.
Chaque vue doit distinguer chargement initial, données obsolètes, erreur et absence de résultat.
Une requête concurrente plus ancienne ne doit pas écraser une réponse récente.
Les dépendances des effets doivent éviter boucles et captures de valeurs périmées.
Les données brutes doivent rester séparées des formats destinés à l’affichage.
Cette séparation facilite audit des calculs et comparaison avec une source externe.

Suite : [03 — Volumes et positions](03-volumes-et-positions.md).
