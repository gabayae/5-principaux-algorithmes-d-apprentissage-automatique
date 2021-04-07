


### <body><right><a href="https://fr.wikipedia.org/wiki/R%C3%A9gression_logistique" ><img src="https://mrmint.fr/wp-content/uploads/2017/09/Sigmoid-function.png" style="float:left; max-width: 80px; display: inline" alt="INSA"/></a></right></body>



Les prédictions de régression linéaire sont des valeurs continues (températures en degrés), les prévisions de régression logistique sont des valeurs discrètes, c’est-à-dire un ensemble fini de valeurs (Vrai ou faux par exemple). La régression logistique convient mieux à la classification binaire. Par exemple, on peut considérer un ensemble de données où y = 0 ou 1, où 1 représente la classe par défaut. Pour illustrer on peut imaginer que l’on veuille prédire si il pleuvra ou non. On aura 1 pour si il pleut et 0 le cas contraire.

Au contraire de la régression linéaire, la régression logistique, propose le résultat sous forme de probabilités de la classe par défaut. Le résultat appartient donc à l’intervalle [0 :1]. C’est-à-dire qu’il est compris entre 0 et 1, vu qu’il s’agit d’une probabilité. La valeur y de sortie est générée par la transformation de la valeur x, à l’aide de la fonction logistique h (x) = 1 / (1 + e ^ -x). Un seuil est ensuite appliqué pour forcer cette probabilité dans une classification binaire.
