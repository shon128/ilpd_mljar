# Summary of 3_Optuna_CatBoost_Stacked

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.2
- **depth**: 9
- **rsm**: 0.9680881637122927
- **loss_function**: Logloss
- **eval_metric**: F1
- **l2_leaf_reg**: 0.17260392951201953
- **random_strength**: 2.790500228738866
- **min_data_in_leaf**: 19
- **num_boost_round**: 1000
- **early_stopping_rounds**: 50
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **k_folds**: 10
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
f1

## Training time

14.9 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.498977 | nan           |
| auc       | 0.858168 | nan           |
| f1        | 0.843091 |   0.505825    |
| accuracy  | 0.838164 |   0.505825    |
| precision | 0.944444 |   0.954927    |
| recall    | 1        |   0.000315148 |
| mcc       | 0.677666 |   0.505825    |


## Confusion matrix (at threshold=0.505825)
|              |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|
| Labeled as 1 |              334 |               80 |
| Labeled as 2 |               54 |              360 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
