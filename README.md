# Summary of 1_Optuna_LightGBM

[<< Go back](../README.md)


## LightGBM
- **n_jobs**: -1
- **objective**: binary
- **num_leaves**: 452
- **learning_rate**: 0.1
- **feature_fraction**: 0.9641128533154418
- **bagging_fraction**: 0.5027760558495366
- **min_data_in_leaf**: 7
- **metric**: custom
- **custom_eval_metric_name**: f1
- **lambda_l1**: 2.892725976120867e-07
- **lambda_l2**: 0.00016752816537790065
- **bagging_freq**: 2
- **extra_trees**: False
- **num_boost_round**: 1000
- **early_stopping_rounds**: 50
- **cat_feature**: []
- **feature_pre_filter**: False
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **k_folds**: 10
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
f1

## Training time

15.5 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.461019 | nan         |
| auc       | 0.869629 | nan         |
| f1        | 0.832184 |   0.496883  |
| accuracy  | 0.823671 |   0.496883  |
| precision | 0.985294 |   0.968086  |
| recall    | 1        |   1.317e-05 |
| mcc       | 0.6507   |   0.496883  |


## Confusion matrix (at threshold=0.496883)
|              |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|
| Labeled as 1 |              320 |               94 |
| Labeled as 2 |               52 |              362 |

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
