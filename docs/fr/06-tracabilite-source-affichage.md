# Traçabilité source-affichage

Chaque métrique doit pouvoir être suivie de l’endpoint brut jusqu’au composant qui l’affiche.
Le contrat de donnée précise champs requis, unité, précision, nullabilité et horodatage.
Les helpers de transformation doivent rester purs afin de comparer entrée et sortie sans contexte caché.
Les aggregations indiquent fenêtre, filtre d’actifs et traitement des sous-comptes.
Le composant conserve fetched_at et source au lieu de ne recevoir qu’un nombre formaté.
Une fiche de provenance réduit les erreurs lors d’un changement d’API ou de schéma.
Les valeurs impossibles sont rejetées avant formatage plutôt que masquées par un arrondi.

Suite : [07 — Précision et grands nombres](07-precision-et-grands-nombres.md).
