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

Pour envoyer Question & Answer au modèle on peut : 
* Séparer question et réponse via un token
* Définir une taille fixe pour la question et pour la réponse et gérer la séparation comme ça 

Métriques : 
Performance à la tâche de prédiction du score : loss mean squared error c'est OK 
KPI (pour choisir le model) : écart moyen entre le score de la réponse prédite et le score de la réponse optimale

