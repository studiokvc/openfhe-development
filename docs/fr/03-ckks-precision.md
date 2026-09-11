# 03 — CKKS et précision approximative

CKKS représente des vecteurs complexes ou réels avec une échelle encodée.
Addition et multiplication propagent à la fois approximation et niveau cryptographique.
Le rescaling réduit l’échelle après multiplication tout en consommant un module.
Deux chiffrés doivent être alignés en niveau et en échelle avant certaines opérations.
Le résultat déchiffré doit être interprété avec une tolérance explicite.
Comparaisons, seuils et branches ne suivent pas naturellement l’arithmétique approximative.
OpenFHE propose le changement de schéma vers FHEW/TFHE pour certaines fonctions non lisses.
Ce passage ajoute toutefois clés d’évaluation, paramètres et coûts à auditer.

Suite : [bootstrapping](04-bootstrapping.md).
