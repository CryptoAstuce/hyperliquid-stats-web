# Cache et fraîcheur

Un cache accélère l’interface mais peut afficher un état différent de la chaîne ou de l’API courante.
Chaque objet dérivé devrait conserver fetched_at, source et plage temporelle.
Le rafraîchissement doit être idempotent et tolérant aux échecs temporaires.
Les pages statiques et composants client n’ont pas les mêmes garanties de mise à jour.
Une invalidation trop agressive surcharge la source ; trop lente, elle trompe l’utilisateur.
Les erreurs partielles doivent rester visibles au lieu de produire un tableau apparemment complet.
La fraîcheur est une propriété de donnée, pas seulement une animation de chargement.

Suite : [05 — Limites et vérification](05-limites-et-verification.md).
