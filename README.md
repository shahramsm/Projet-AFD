# Projet-AFD
projet analyse et fouille des données





Partie 1:

 

Tout d’abord,  vous vous intéresserez à un jeu de données décrivant le score de différentes applications Android. Ce jeu de données est disponible ici: https://www.kaggle.com/lava18/google-play-store-apps

 

En utilisant scikit-Learn, exécutez une régression linéaire pour prédire le champs « Rating » de ces données. Analysez et expliquez les résultats le mieux possible. Si possible, proposez des solutions pour améliorer la prédiction.

 

 

Partie 2:

 

Ensuite, vous travaillerez sur des données décrivant la performance d’étudiants aux examens:

https://www.kaggle.com/spscientist/students-performance-in-exams

 

1) Toujours avec scikit-learn, lancez l'algorithme du k-means, et interprétez les résultats. Faites de même avec l’algorithme de mixture de gaussienne.

2) Ensuite, on cherchera à prédire si le « math score » est supérieur au score médian, en fonction des autres variables. Ca sera donc un problème de classification bi-classe: la classe 0 (math score inférieur au score médian) et la classe 1 (math score supérieur ou égal au score médian).

    - D’abord, implémentez vous-meme (sans scikit-learn, juste avec Python+numpy) l’algorithme du 1-plus-proche voisin sur ces données, et analysez les résultats.

    - Ensuite, implémentez vous-même l’algorithme Bayesien naif (sans scikit-learn) sur les 5 premières variables catégorielles, pour prédire si le « math score » est supérieur au score médian. N’oubliez pas de commenter votre code.

    - Puis, implémentez vous-même l’algorithme "gaussian naive bayes" (sans scikit-learn) sur les  variables continues restantes, pour prédire si le « math score » est supérieur au score médian.

    - avec scikit-learn, appliquez la régression logistique pour ce même problème de prédiction. N’oubliez pas de commenter et d’analyser les résultats.



