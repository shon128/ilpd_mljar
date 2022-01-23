# AutoML Leaderboard

| Best model   | name                                                                       | model_type     | metric_type   |   metric_value |   train_time |
|:-------------|:---------------------------------------------------------------------------|:---------------|:--------------|---------------:|-------------:|
|              | [1_Optuna_LightGBM](1_Optuna_LightGBM/README.md)                           | LightGBM       | f1            |       0.834101 |        16.7  |
|              | [2_Optuna_Xgboost](2_Optuna_Xgboost/README.md)                             | Xgboost        | f1            |       0.792669 |        29.27 |
|              | [3_Optuna_CatBoost](3_Optuna_CatBoost/README.md)                           | CatBoost       | f1            |       0.837529 |        15.06 |
|              | [4_Optuna_NeuralNetwork](4_Optuna_NeuralNetwork/README.md)                 | Neural Network | f1            |       0.764317 |        17.42 |
|              | [5_Optuna_RandomForest](5_Optuna_RandomForest/README.md)                   | Random Forest  | f1            |       0.818182 |        16.15 |
|              | [6_Optuna_ExtraTrees](6_Optuna_ExtraTrees/README.md)                       | Extra Trees    | f1            |       0.820112 |        15.33 |
|              | [Ensemble](Ensemble/README.md)                                             | Ensemble       | f1            |       0.837529 |         0.72 |
|              | [3_Optuna_CatBoost_Stacked](3_Optuna_CatBoost_Stacked/README.md)           | CatBoost       | f1            |       0.844444 |        16.07 |
|              | [1_Optuna_LightGBM_Stacked](1_Optuna_LightGBM_Stacked/README.md)           | LightGBM       | f1            |       0.843114 |        13.42 |
|              | [6_Optuna_ExtraTrees_Stacked](6_Optuna_ExtraTrees_Stacked/README.md)       | Extra Trees    | f1            |       0.843713 |        15.86 |
| **the best** | [5_Optuna_RandomForest_Stacked](5_Optuna_RandomForest_Stacked/README.md)   | Random Forest  | f1            |       0.854438 |        17.47 |
|              | [2_Optuna_Xgboost_Stacked](2_Optuna_Xgboost_Stacked/README.md)             | Xgboost        | f1            |       0.830325 |        23.95 |
|              | [4_Optuna_NeuralNetwork_Stacked](4_Optuna_NeuralNetwork_Stacked/README.md) | Neural Network | f1            |       0.798165 |        16.07 |
|              | [Ensemble_Stacked](Ensemble_Stacked/README.md)                             | Ensemble       | f1            |       0.854438 |         0.92 |

### AutoML Performance
![AutoML Performance](ldb_performance.png)

### AutoML Performance Boxplot
![AutoML Performance Boxplot](ldb_performance_boxplot.png)

### Spearman Correlation of Models
![models spearman correlation](correlation_heatmap.png)

