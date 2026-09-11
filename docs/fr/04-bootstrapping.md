# 04 — Bootstrapping et renouvellement

Le bootstrapping évalue homomorphiquement le déchiffrement pour rafraîchir un chiffré.
Il restaure de la capacité de calcul sans révéler le message.
Dans CKKS, cette opération reste approximative et ajoute sa propre erreur.
La configuration prépare des clés d’évaluation et des dimensions adaptées aux rotations.
Les étapes ModRaise, transformation de coefficients et réduction modulaire ont des coûts distincts.
Le bootstrapping fonctionnel de FHEW/TFHE peut aussi évaluer une table pendant le rafraîchissement.
La fréquence de rafraîchissement influence fortement latence et mémoire.
Elle doit être intégrée au graphe de calcul, pas ajoutée après coup.

Suite : [clés, seuil et limites](05-cles-limites.md).
