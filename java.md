vm
==

stack
---
1 stack par thread. Gère variables locales, paramètres, etc... mais pas les objet. Peut causer un StackOverflow.

Elle est accéssible comme une stack, en lifo. Ce qui fait qu'il est assez simple de la gérer.

heap
---
stocke tous les objets et tableaux. Elle est partagée par toutes les threads.

Elle est accéssible par adréssage (à vérifier), donc son état peut vite devenir compliqué.

référence : http://www.jmdoudoux.fr/java/dej/chap-jvm.htm
