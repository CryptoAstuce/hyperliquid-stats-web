# Source des statistiques

L interface Next.js transforme des donnees Hyperliquid en tableaux et visualisations publiques.
Une statistique fiable commence par identifier sa source, sa periode et son instant de rafraichissement.
Les appels distants doivent distinguer erreurs reseau, reponses partielles et donnees legitimement vides.
Les constantes definissent actifs, libelles et conventions reutilises dans plusieurs vues.
Les helpers normalisent nombres et dates avant leur presentation.
Une valeur agregee ne doit pas masquer son unite ni son denominateur.
Le front-end ne constitue pas a lui seul une source canonique du protocole.

Suite : [02 — Flux de données React](02-flux-de-donnees-react.md).
