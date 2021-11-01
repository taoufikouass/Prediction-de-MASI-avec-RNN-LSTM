### Prédiction de l'indice boursier MASI à l'aide d'un réseau neuronal récurrent LSTM
La prévision de l'évolution des cours boursiers est un sujet central de l'ingénierie financière. Compte tenu de la complexité et de la non-linéarité des processus sous-jacents, nous envisageons l'utilisation de réseaux de neurones.
Les LSTM sont très puissants dans les problèmes de prédiction de séquence car ils sont capables de stocker des informations passées. C'est important dans notre cas, car le prix précédent d'une action est crucial pour prédire le prix futur.

### Sommaire
1. Import libraries.
2. Importation des données historiques de MASI.
3. Préparer les données pour LSTM.
* Normalisation des données
* Transformation des données
4. Construction du modèle : LSTM
* Training
* Predictions
5. Conclusion. 
