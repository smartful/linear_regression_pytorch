# Régression linéaire avec PyTorch

Exemple de régression linéaire avec PyTorch.

- On simule la création de données immobilières (couple mêtre carré / prix).
- On crée un modèle de regression linéaire : f(x) = wx + b (w: weight, b: bias).
- On calcul l'erreur des moindre carré (via la fonction MSELoss()).
- On met à jour les paramètres : w et b (via la fonction SGD()).
- On affiche les résultats, dont le coefficient de détermination pour évaluer notre régression.
