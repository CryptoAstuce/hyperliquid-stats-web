# États dégradés

Une panne partielle ne doit pas produire un tableau visuellement complet avec des zéros inventés.
L’interface distingue stale, partial, unavailable et empty avec des messages différents.
La dernière valeur valide peut rester visible si son âge et l’échec du rafraîchissement sont affichés.
Les requêtes concurrentes portent un identifiant ou signal d’annulation pour rejeter une réponse tardive.
Un changement de compte, marché ou fenêtre invalide les résultats de la sélection précédente.
Les erreurs de parsing sont séparées des erreurs HTTP afin de détecter une dérive de schéma.
Ces états améliorent la confiance sans prétendre transformer l’interface en oracle.

Périmètre : lecture documentaire ; aucun appel API, build ou test n’a été exécuté.
