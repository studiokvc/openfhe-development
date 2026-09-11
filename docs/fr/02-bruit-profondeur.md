# 02 — Profondeur multiplicative et bruit

Chaque opération homomorphe fait évoluer le bruit contenu dans le chiffré.
Les multiplications consomment davantage de profondeur que les additions.
La chaîne de modules et les paramètres du contexte déterminent le budget disponible.
Une profondeur insuffisante mène à un déchiffrement incorrect ou inutilisable.
Un surdimensionnement augmente coût, mémoire et taille des clés.
La relinéarisation réduit la croissance structurelle après multiplication.
La planification doit suivre le pire chemin du circuit, pas seulement un exemple moyen.
Les paramètres de démonstration ne doivent pas être repris aveuglément en production.

Suite : [CKKS et précision](03-ckks-precision.md).
