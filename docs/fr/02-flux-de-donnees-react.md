# Flux de donnees React

Les contexts partagent etat et resultats entre composants sans multiplier les requetes.
Les hooks encapsulent chargement, rafraichissement et transformation des series.
Chaque vue doit distinguer chargement initial, donnees obsoletes, erreur et absence de resultat.
Une requete concurrente plus ancienne ne doit pas ecraser une reponse recente.
Les dependances des effets doivent eviter boucles et captures de valeurs perimees.
Les donnees brutes doivent rester separees des formats destines a l affichage.
Cette separation facilite audit des calculs et comparaison avec une source externe.

Suite : [03 — Volumes et positions](03-volumes-et-positions.md).
