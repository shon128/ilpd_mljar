# Summary of 4_Optuna_NeuralNetwork_Stacked

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 91
- **dense_2_size**: 91
- **learning_rate**: 0.05
- **learning_rate_type**: constant
- **alpha**: 0.0014388557265717062
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **k_folds**: 10
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
f1

## Training time

15.1 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.577506 | nan           |
| auc       | 0.839944 | nan           |
| f1        | 0.806271 |   0.440738    |
| accuracy  | 0.791063 |   0.440738    |
| precision | 0.846667 |   0.86252     |
| recall    | 1        |   8.66331e-31 |
| mcc       | 0.589436 |   0.440738    |


## Confusion matrix (at threshold=0.440738)
|              |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|
| Labeled as 1 |              295 |              119 |
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
