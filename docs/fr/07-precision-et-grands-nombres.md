# Precision et grands nombres

Les prix, tailles et notionnels ne doivent pas transiter prematurement par Number si leur precision le depasse.
Les chaines decimales sont parsees avec une politique explicite avant tout calcul.
Le formatage monetaire intervient seulement apres aggregation, jamais entre deux operations.
Les ratios traitent separement denominateur nul, donnee absente et valeur effectivement egale a zero.
Les conversions base/quote conservent le sens du marche et l unite de taille.
Un arrondi d affichage ne doit pas etre reutilise comme entree d un autre indicateur.
Des exemples limites documentent tres grands notionnels, petites tailles et valeurs negatives autorisees.

Suite : [08 — États dégradés](08-etats-degrades.md).
