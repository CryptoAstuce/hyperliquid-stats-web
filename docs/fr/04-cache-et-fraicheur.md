# Cache et fraicheur

Un cache accelere l interface mais peut afficher un etat different de la chaine ou de l API courante.
Chaque objet derive devrait conserver fetched_at, source et plage temporelle.
Le rafraichissement doit etre idempotent et tolerant aux echecs temporaires.
Les pages statiques et composants client n ont pas les memes garanties de mise a jour.
Une invalidation trop agressive surcharge la source ; trop lente, elle trompe l utilisateur.
Les erreurs partielles doivent rester visibles au lieu de produire un tableau apparemment complet.
La fraicheur est une propriete de donnee, pas seulement une animation de chargement.

Suite : [05 — Limites et verification](05-limites-et-verification.md).
