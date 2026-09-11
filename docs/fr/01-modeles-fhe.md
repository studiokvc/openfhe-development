# 01 — Choisir le bon modèle FHE

OpenFHE rassemble plusieurs familles adaptées à des calculs différents.
BFV et BGV ciblent principalement l’arithmétique entière exacte.
CKKS encode des valeurs réelles de façon approximative.
FHEW et TFHE privilégient portes booléennes et évaluations par tables.
Le choix du schéma fixe la sémantique des résultats autant que leurs performances.
Une application financière ne doit pas traiter une approximation CKKS comme une égalité exacte.
Le contexte cryptographique porte paramètres, clés et opérations autorisées.
Cette décision doit être prise à partir du calcul métier et du modèle de menace.

Suite : [profondeur et bruit](02-bruit-profondeur.md).
