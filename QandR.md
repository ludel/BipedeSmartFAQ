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


## Q et R 05/03/2021

Métriques : 
Performance à la tâche de prédiction du score : loss mean squared error c'est OK 
KPI (pour choisir le model) : écart moyen entre le score de la réponse prédite et le score de la réponse optimale

## Q et R 19/03/2021
Word2Vec implémenté mais pas encore de transfert learning
Word2vec n'a pas forcément besoin de transfert learning 

Suggestions : 
* Comparer avec un modèle word2vec déjà entrainé
* On prend word2vec entrainé
* Chercher des lib qui implémentent déjà W2V / Retrouver code original de W2V 
* Article medium qui explique comment l'appliquer 

* Transformers n'ont pas besoin de W2V à priori dans la plupart des cas
* -> Huggingface
* On va trouver facilement des ex pour l'utiliser
* Met trop de tps à être entrainé
* Trouver un bon modèle => google, medium (regression sur des textes)  
            => piperwithcode site que maxime a fourni 
            
* SOUTENANCE : rôle de datascientist
* COmparer toutes les méthodes testées
* Quelles est la méthode que nous consillons ?
* Montrer que la méthode est la meilleure
* On peut parler de notion financière : coût de mise en place / jeu de données qu'on a pas forcément
