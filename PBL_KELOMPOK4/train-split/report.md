# Dataset
Total Images: 10899
Dataset have been applied with Auto Brightness & contras + clahe and segmented, but trained with hyperparameter: label_smoothing = 0.05

Class:
Sayur_Akar          
Sayur_Buah         
Sayur_Bunga         
Sayur_Daun          
Sayur_Polong        


# Split Train 20%
## MLP
Train Accuracy: 93.45%
Val Accuracy: 94.60%
Best Validation Accuracy: 94.79%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.95      0.98      0.97      1988
  Sayur_Buah       0.96      0.96      0.96      4496
 Sayur_Bunga       0.97      0.89      0.93      1226
  Sayur_Daun       0.85      0.92      0.88       790
Sayur_Polong       0.83      0.67      0.74       217

    accuracy                           0.95      8717
   macro avg       0.91      0.89      0.90      8717
weighted avg       0.95      0.95      0.95      8717

## SVM
Train Accuracy: 99.40%
Val Accuracy:   94.65%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.96      0.98      0.97      1988
  Sayur_Buah       0.94      0.97      0.96      4496
 Sayur_Bunga       0.96      0.90      0.93      1226
  Sayur_Daun       0.92      0.88      0.90       790
Sayur_Polong       0.86      0.63      0.73       217

    accuracy                           0.95      8717
   macro avg       0.93      0.87      0.90      8717
weighted avg       0.95      0.95      0.95      8717

## EfficientNetV2-S
Train Accuracy: 88.59%
Val Accuracy: 91.56%
Best Validation Accuracy: 91.60%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.95      0.98      0.97      1988
  Sayur_Buah       0.92      0.97      0.95      4496
 Sayur_Bunga       0.91      0.87      0.89      1226
  Sayur_Daun       0.79      0.76      0.78       790
Sayur_Polong       0.00      0.00      0.00       217

    accuracy                           0.92      8717
   macro avg       0.72      0.72      0.72      8717
weighted avg       0.89      0.92      0.90      8717


# Split Train 30%
## MLP
Train Accuracy: 94.83%
Val Accuracy: 95.66%
Best Validation Accuracy: 95.79%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.95      0.99      0.97      1740
  Sayur_Buah       0.97      0.97      0.97      3933
 Sayur_Bunga       0.97      0.93      0.95      1073
  Sayur_Daun       0.89      0.93      0.91       691
Sayur_Polong       0.95      0.69      0.80       190

    accuracy                           0.96      7627
   macro avg       0.95      0.90      0.92      7627
weighted avg       0.96      0.96      0.96      7627

## SVM
Train Accuracy: 99.08%
Val Accuracy:   95.44% 

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.96      0.98      0.97      1740
  Sayur_Buah       0.96      0.97      0.96      3933
 Sayur_Bunga       0.97      0.93      0.95      1073
  Sayur_Daun       0.92      0.89      0.90       691
Sayur_Polong       0.95      0.69      0.80       190

    accuracy                           0.95      7627
   macro avg       0.95      0.89      0.92      7627
weighted avg       0.95      0.95      0.95      7627

## EfficientNetV2-S
Train Accuracy: 96.58%
Val Accuracy: 95.41%
Best Validation Accuracy: 95.69%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.97      0.99      0.98      1740
  Sayur_Buah       0.95      0.98      0.97      3933
 Sayur_Bunga       0.97      0.90      0.94      1073
  Sayur_Daun       0.93      0.90      0.92       691
Sayur_Polong       0.96      0.52      0.68       190

    accuracy                           0.95      7627
   macro avg       0.95      0.86      0.89      7627
weighted avg       0.95      0.95      0.95      7627

# Split Train 40%
## MLP
Train Accuracy: 96.29%
Val Accuracy: 96.39%
Best Validation Accuracy: 96.67%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.97      0.99      0.98      1491
  Sayur_Buah       0.98      0.97      0.97      3372
 Sayur_Bunga       0.97      0.94      0.95       919
  Sayur_Daun       0.88      0.95      0.91       592
Sayur_Polong       0.96      0.75      0.85       163

    accuracy                           0.96      6537
   macro avg       0.95      0.92      0.93      6537
weighted avg       0.96      0.96      0.96      6537

## SVM
Train Accuracy: 99.40%
Val Accuracy:   96.05%  

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.97      0.98      0.98      1491
  Sayur_Buah       0.97      0.97      0.97      3372
 Sayur_Bunga       0.96      0.94      0.95       919
  Sayur_Daun       0.90      0.92      0.91       592
Sayur_Polong       0.93      0.80      0.86       163

    accuracy                           0.96      6537
   macro avg       0.94      0.92      0.93      6537
weighted avg       0.96      0.96      0.96      6537

## EfficientNetV2-S
Train Accuracy: 94.64%
Val Accuracy: 94.80%
Best Validation Accuracy: 94.91%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.95      0.98      0.97      1491
  Sayur_Buah       0.97      0.96      0.96      3372
 Sayur_Bunga       0.94      0.91      0.93       919
  Sayur_Daun       0.88      0.93      0.90       592
Sayur_Polong       0.76      0.63      0.69       163

    accuracy                           0.95      6537
   macro avg       0.90      0.88      0.89      6537
weighted avg       0.95      0.95      0.95      6537

# Split Train 50%
## MLP
Train Accuracy: 95.85%
Val Accuracy: 97.52%
Best Validation Accuracy: 97.52%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.98      0.99      0.99      1243
  Sayur_Buah       0.98      0.98      0.98      2810
 Sayur_Bunga       0.98      0.95      0.96       766
  Sayur_Daun       0.93      0.96      0.94       494
Sayur_Polong       0.95      0.86      0.90       136

    accuracy                           0.98      5449
   macro avg       0.96      0.95      0.96      5449
weighted avg       0.98      0.98      0.98      5449

## SVM
Train Accuracy: 99.17%
Val Accuracy:   96.99% 

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.98      0.99      0.99      1243
  Sayur_Buah       0.97      0.98      0.98      2810
 Sayur_Bunga       0.98      0.95      0.96       766
  Sayur_Daun       0.93      0.92      0.92       494
Sayur_Polong       0.94      0.86      0.90       136

    accuracy                           0.97      5449
   macro avg       0.96      0.94      0.95      5449
weighted avg       0.97      0.97      0.97      5449

## EfficientNetV2-S
Train Accuracy: 97.32%
Val Accuracy: 97.38%
Best Validation Accuracy: 97.38%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.98      0.99      0.98      1243
  Sayur_Buah       0.98      0.99      0.98      2810
 Sayur_Bunga       0.97      0.95      0.96       766
  Sayur_Daun       0.94      0.94      0.94       494
Sayur_Polong       0.90      0.91      0.91       136

    accuracy                           0.97      5449
   macro avg       0.95      0.95      0.95      5449
weighted avg       0.97      0.97      0.97      5449

# Split Train 60%
## MLP
Train Accuracy: 96.74%
Val Accuracy: 97.75%
Best Validation Accuracy: 97.75%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.98      0.99      0.99       994
  Sayur_Buah       0.98      0.98      0.98      2248
 Sayur_Bunga       0.98      0.96      0.97       613
  Sayur_Daun       0.92      0.98      0.95       395
Sayur_Polong       0.98      0.83      0.90       108

    accuracy                           0.98      4358
   macro avg       0.97      0.95      0.96      4358
weighted avg       0.98      0.98      0.98      4358

## SVM
Train Accuracy: 99.22%
Val Accuracy:   96.60%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.98      0.99      0.98       994
  Sayur_Buah       0.97      0.98      0.97      2248
 Sayur_Bunga       0.97      0.94      0.96       613
  Sayur_Daun       0.91      0.92      0.92       395
Sayur_Polong       0.98      0.81      0.88       108

    accuracy                           0.97      4358
   macro avg       0.96      0.93      0.94      4358
weighted avg       0.97      0.97      0.97      4358

## EfficientNetV2-S
Train Accuracy: 99.34%
Val Accuracy: 98.62%
Best Validation Accuracy: 98.62%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.99      0.99      0.99       994
  Sayur_Buah       0.99      0.99      0.99      2248
 Sayur_Bunga       0.98      0.97      0.98       613
  Sayur_Daun       0.95      0.99      0.97       395
Sayur_Polong       0.98      0.92      0.95       108

    accuracy                           0.99      4358
   macro avg       0.98      0.97      0.98      4358
weighted avg       0.99      0.99      0.99      4358

# Split Train 70%

## MLP
Train Accuracy: 96.97%
Val Accuracy: 97.92%
Best Validation Accuracy: 97.92%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.99      1.00      0.99       745
  Sayur_Buah       0.99      0.99      0.99      1686
 Sayur_Bunga       0.99      0.95      0.97       459
  Sayur_Daun       0.91      0.96      0.94       296
Sayur_Polong       1.00      0.89      0.94        81

    accuracy                           0.98      3267
   macro avg       0.97      0.96      0.96      3267
weighted avg       0.98      0.98      0.98      3267

## SVM
Train Accuracy: 99.19%
Val Accuracy:   96.57%   

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.98      0.99      0.98       745
  Sayur_Buah       0.97      0.98      0.97      1686
 Sayur_Bunga       0.96      0.95      0.95       459
  Sayur_Daun       0.90      0.91      0.91       296
Sayur_Polong       1.00      0.84      0.91        81

    accuracy                           0.97      3267
   macro avg       0.96      0.93      0.95      3267
weighted avg       0.97      0.97      0.97      3267

## EfficientNetV2-S
Train Accuracy: 99.42%
Val Accuracy: 98.47%
Best Validation Accuracy: 98.47%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.99      1.00      0.99       745
  Sayur_Buah       0.99      0.99      0.99      1686
 Sayur_Bunga       0.99      0.95      0.97       459
  Sayur_Daun       0.98      0.97      0.97       296
Sayur_Polong       0.90      0.94      0.92        81

    accuracy                           0.98      3267
   macro avg       0.97      0.97      0.97      3267
weighted avg       0.98      0.98      0.98      3267

# Split Train 80%
## MLP
Train Accuracy: 96.89%
Val Accuracy: 97.75%
Best Validation Accuracy: 97.98%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.97      0.99      0.98       497
  Sayur_Buah       0.98      0.99      0.98      1124
 Sayur_Bunga       0.99      0.95      0.97       306
  Sayur_Daun       0.95      0.96      0.96       197
Sayur_Polong       0.91      0.89      0.90        54

    accuracy                           0.98      2178
   macro avg       0.96      0.96      0.96      2178
weighted avg       0.98      0.98      0.98      2178

## SVM
Train Accuracy: 99.22%
Val Accuracy:   96.97%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.98      0.99      0.98       497
  Sayur_Buah       0.97      0.98      0.98      1124
 Sayur_Bunga       0.96      0.95      0.96       306
  Sayur_Daun       0.94      0.92      0.93       197
Sayur_Polong       0.96      0.89      0.92        54

    accuracy                           0.97      2178
   macro avg       0.96      0.95      0.95      2178
weighted avg       0.97      0.97      0.97      2178

## EfficientNetV2-S
Train Accuracy: 99.55%
Val Accuracy: 98.53%
Best Validation Accuracy: 98.62%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.99      1.00      0.99       497
  Sayur_Buah       0.99      0.99      0.99      1124
 Sayur_Bunga       0.98      0.95      0.96       306
  Sayur_Daun       0.96      0.97      0.96       197
Sayur_Polong       0.94      0.93      0.93        54

    accuracy                           0.99      2178
   macro avg       0.97      0.97      0.97      2178
weighted avg       0.99      0.99      0.99      2178


# Split Train 90%
## MLP
Train Accuracy: 97.54%
Val Accuracy: 97.43%
Best Validation Accuracy: 97.89%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      0.98      0.99       248
  Sayur_Buah       0.97      0.99      0.98       562
 Sayur_Bunga       0.97      0.94      0.96       153
  Sayur_Daun       0.94      0.97      0.95        98
Sayur_Polong       1.00      0.81      0.90        27

    accuracy                           0.97      1088
   macro avg       0.98      0.94      0.96      1088
weighted avg       0.97      0.97      0.97      1088

## SVM
Train Accuracy: 99.29%
Val Accuracy:   95.77% 

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.98      0.97      0.98       248
  Sayur_Buah       0.96      0.98      0.97       562
 Sayur_Bunga       0.95      0.93      0.94       153
  Sayur_Daun       0.92      0.90      0.91        98
Sayur_Polong       0.95      0.78      0.86        27

    accuracy                           0.96      1088
   macro avg       0.95      0.91      0.93      1088
weighted avg       0.96      0.96      0.96      1088

## EfficientNetV2-S
Train Accuracy: 99.75%
Val Accuracy: 99.26%
Best Validation Accuracy: 99.45%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      0.99      0.99       248
  Sayur_Buah       1.00      0.99      1.00       562
 Sayur_Bunga       0.97      1.00      0.99       153
  Sayur_Daun       0.98      1.00      0.99        98
Sayur_Polong       1.00      0.93      0.96        27

    accuracy                           0.99      1088
   macro avg       0.99      0.98      0.99      1088
weighted avg       0.99      0.99      0.99      1088


# Split Train 95%
## MLP
Train Accuracy: 97.63%
Val Accuracy: 98.16%
Best Validation Accuracy: 98.53%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.99      0.98      0.98       124
  Sayur_Buah       0.99      0.99      0.99       281
 Sayur_Bunga       0.99      0.95      0.97        76
  Sayur_Daun       0.94      1.00      0.97        49
Sayur_Polong       0.92      0.92      0.92        13

    accuracy                           0.98       543
   macro avg       0.97      0.97      0.97       543
weighted avg       0.98      0.98      0.98       543

## SVM
Train Accuracy: 99.14%
Val Accuracy:   97.05%  

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.98      0.98      0.98       124
  Sayur_Buah       0.97      0.99      0.98       281
 Sayur_Bunga       0.99      0.93      0.96        76
  Sayur_Daun       0.98      0.92      0.95        49
Sayur_Polong       0.86      0.92      0.89        13

    accuracy                           0.97       543
   macro avg       0.95      0.95      0.95       543
weighted avg       0.97      0.97      0.97       543

## EfficientNetV2-S
Train Accuracy: 99.62%
Val Accuracy: 98.53%
Best Validation Accuracy: 98.71%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      0.98      0.99       124
  Sayur_Buah       0.99      0.99      0.99       281
 Sayur_Bunga       1.00      0.99      0.99        76
  Sayur_Daun       0.96      0.96      0.96        49
Sayur_Polong       0.87      1.00      0.93        13

    accuracy                           0.99       543
   macro avg       0.96      0.98      0.97       543
weighted avg       0.99      0.99      0.99       543