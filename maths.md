Bloom Filters
===
permet de savoir:
* avec certitude qu'un élement n'est pas dans un ensemble (aucun faux negatif)
* avec une certaine probabilité que l'élément peut être présent dans l'ensemble (qq faux positif)

La taille du filtre est indépendante de la taille de la structure contenant l'ensemble.

Plus l'ensemble contient d'éléments, plus il y a de faux positifs.

Ce genre de filtre permet d'éviter des appels inutiles à une très grande base de données en vérifiant tout de suite qu'une ligne recherchée n'y est pas présente.
