## Q et R 26/02/2021
Cas d'usage : mapper une question à une reponse  
Pour chacune des question trouver la meilleur réponse (meilleur score) 

Approche 1
Similarité entre questions : 
* Representation sous forme de features des questions 
* Calculer la distance entre ces représentations

Approche 2
Présenter au modèle un couple Question - Réponse n parmi N réponses
Prédire la pertinence de chaque réponse à cette question et retourner la meilleure
