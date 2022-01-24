# Summary of Ensemble_Stacked

[<< Go back](../README.md)


## Ensemble structure
| Model                         |   Weight |
|:------------------------------|---------:|
| 5_Optuna_RandomForest_Stacked |        1 |

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.45042  |  nan        |
| auc       | 0.895528 |  nan        |
| f1        | 0.854438 |    0.500422 |
| accuracy  | 0.851449 |    0.500422 |
| precision | 0.952381 |    0.963346 |
| recall    | 0.992754 |    0        |
| mcc       | 0.703492 |    0.500422 |


## Confusion matrix (at threshold=0.500422)
|              |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|
| Labeled as 1 |              344 |               70 |
| Labeled as 2 |               53 |              361 |

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
