# rumor-propagation

Considérons la propagation d'une rumeur dans une entreprise de 1500 employés, travaillant tous dans le même bâtiment. Supposons que la propagation de la rumeur soit similaire à la propagation d'une maladie contagieuse, c'est-à-dire que le nombre de personnes qui écoutent la rumeur de chaque jour est proportionnel au produit du nombre de personnes qui ont entendu la rumeur auparavant et du nombre de personnes qui n'ont pas entendu la rumeur. Ceci est donné par :

$ r_{n+1} = r_{n} + kr_{n}(1500-r_{n}) $

