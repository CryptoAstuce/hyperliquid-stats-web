# Précision et grands nombres

Les prix, tailles et notionnels ne doivent pas transiter prématurément par Number si leur précision le dépasse.
Les chaînes décimales sont parsées avec une politique explicite avant tout calcul.
Le formatage monétaire intervient seulement après aggregation, jamais entre deux opérations.
Les ratios traitent séparément dénominateur nul, donnée absente et valeur effectivement égale à zéro.
Les conversions base/quote conservent le sens du marché et l’unité de taille.
Un arrondi d’affichage ne doit pas être réutilisé comme entrée d’un autre indicateur.
Des exemples limites documentent très grands notionnels, petites tailles et valeurs négatives autorisées.

Suite : [08 — États dégradés](08-etats-degrades.md).
