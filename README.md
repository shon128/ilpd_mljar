# Summary of 2_Optuna_Xgboost

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.025
- **max_depth**: 8
- **min_child_weight**: 1
- **subsample**: 0.4379373714678372
- **colsample_bytree**: 0.8753138582839219
- **eval_metric**: f1
- **lambda**: 0.12046576655376649
- **alpha**: 0.0005573981741589326
- **max_rounds**: 1000
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

27.8 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.470986 | nan         |
| auc       | 0.866736 | nan         |
| f1        | 0.793651 |   0.484394  |
| accuracy  | 0.801932 |   0.623025  |
| precision | 0.976744 |   0.867602  |
| recall    | 1        |   0.0121952 |
| mcc       | 0.609879 |   0.623025  |


## Confusion matrix (at threshold=0.623025)
|              |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|
| Labeled as 1 |              361 |               53 |
| Labeled as 2 |              111 |              303 |

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
