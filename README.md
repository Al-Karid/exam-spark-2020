# exam-spark
Examen pratique de ML avec Spark/Sklearn

<hr>

1. RESULTATS EXERCICE 1, les scores en test

| METHODE DE REGRESSION                  | SCORE (MSE)     |
| -------------------------------------- | --------------- |
| régression linéaire                    | 15.65           |
| **METHODES NON LINERAIRES**            | **SCORE (MSE)** |
| forets aléatoires                      | 9.15            |
| SVM                                    | 55.47           |
| **METHODES NON LINERAIRES **GRIDSEARCH | **SCORE (MSE)** |
| forets aléatoires                      | 8.29            |
| SVM                                    | 16.13           |

Le meilleur model est random forest en avec les parametres de grid search suivants: 

**{'max_depth': 20, 'n_estimators': 70}**

<hr>

2. RESULTATS EXERCICE 1, les scores en test

| METHODES DE CLASSIFICATION | SCORES (PRECISION, RECALL)    |
| -------------------------- | ----------------------------- |
| RANDOM FOREST              | precision: 1.00, recall: 0.91 |
| LOGISTIC REGRESISON        | precision: 0.91, recall: 0.91 |
| SVM                        | precision: 0.50, recall: 0.04 |

