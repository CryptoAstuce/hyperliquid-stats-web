# Tracabilite source-affichage

Chaque metrique doit pouvoir etre suivie de l endpoint brut jusqu au composant qui l affiche.
Le contrat de donnee precise champs requis, unite, precision, nullabilite et horodatage.
Les helpers de transformation doivent rester purs afin de comparer entree et sortie sans contexte cache.
Les aggregations indiquent fenetre, filtre d actifs et traitement des sous-comptes.
Le composant conserve fetched_at et source au lieu de ne recevoir qu un nombre formate.
Une fiche de provenance reduit les erreurs lors d un changement d API ou de schema.
Les valeurs impossibles sont rejetees avant formatage plutot que masquees par un arrondi.

Suite : [07 — Précision et grands nombres](07-precision-et-grands-nombres.md).
