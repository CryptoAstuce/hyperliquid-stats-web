# Volumes et positions

Le volume notionnel combine prix et taille mais ne mesure ni profit ni risque a lui seul.
Les classements doivent preciser fenetre temporelle, actifs inclus et traitement des adresses.
Une position ouverte differe d un flux de trades et ne doit pas etre additionnee au volume.
Les liquidations sont des evenements distincts dont le contexte de marge peut manquer au front-end.
Les valeurs USD exigent une politique de prix et un horodatage cohérents.
Les grands nombres doivent etre calcules avant formatage et non depuis une chaine arrondie.
Les pourcentages doivent exposer leur base de comparaison et le cas du denominateur nul.

Suite : [04 — Cache et fraicheur](04-cache-et-fraicheur.md).
