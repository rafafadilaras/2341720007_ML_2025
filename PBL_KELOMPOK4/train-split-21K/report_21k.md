# Split Train 20%
Total Images: 21000K
Dataset without filter or segementation applied, but trained with hyperparameter: label_smoothing = 0.1

Class:
Sayur_Akar          
Sayur_Buah         
Sayur_Bunga         
Sayur_Daun          
Sayur_Polong  


## MLP
Train Accuracy: 95.02%
Val Accuracy: 97.14%
Best Validation Accuracy: 97.33%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.99      0.99      0.99      3360
  Sayur_Buah       0.97      0.99      0.98      8960
 Sayur_Bunga       0.97      0.92      0.95      2240
  Sayur_Daun       0.94      0.90      0.92      1120
Sayur_Polong       0.97      0.96      0.97      1120

    accuracy                           0.97     16800
   macro avg       0.97      0.95      0.96     16800
weighted avg       0.97      0.97      0.97     16800

## SVM
Train Accuracy: 99.17%
Val Accuracy:   97.13%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.99      0.99      0.99      3360
  Sayur_Buah       0.97      0.99      0.98      8960
 Sayur_Bunga       0.97      0.95      0.96      2240
  Sayur_Daun       0.95      0.86      0.90      1120
Sayur_Polong       0.97      0.97      0.97      1120

    accuracy                           0.97     16800
   macro avg       0.97      0.95      0.96     16800
weighted avg       0.97      0.97      0.97     16800

## EfficientNetV2-S
Train Accuracy: 91.90%
Val Accuracy: 94.67%
Best Validation Accuracy: 94.67%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.97      0.99      0.98      3360
  Sayur_Buah       0.95      0.97      0.96      8960
 Sayur_Bunga       0.92      0.87      0.90      2240
  Sayur_Daun       0.92      0.86      0.89      1120
Sayur_Polong       0.93      0.84      0.88      1120

    accuracy                           0.95     16800
   macro avg       0.94      0.91      0.92     16800
weighted avg       0.95      0.95      0.95     16800


# Split Train 30%
## MLP
Train Accuracy: 96.40%
Val Accuracy: 97.91%
Best Validation Accuracy: 97.92%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.99      0.99      0.99      2940
  Sayur_Buah       0.98      0.99      0.98      7839
 Sayur_Bunga       0.96      0.96      0.96      1959
  Sayur_Daun       0.96      0.94      0.95       979
Sayur_Polong       0.97      0.97      0.97       979

    accuracy                           0.98     14696
   macro avg       0.97      0.97      0.97     14696
weighted avg       0.98      0.98      0.98     14696

## SVM
Train Accuracy: 99.43%
Val Accuracy:   97.88%  

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.99      0.99      0.99      2940
  Sayur_Buah       0.98      0.99      0.98      7839
 Sayur_Bunga       0.97      0.95      0.96      1959
  Sayur_Daun       0.97      0.91      0.94       979
Sayur_Polong       0.99      0.97      0.98       979

    accuracy                           0.98     14696
   macro avg       0.98      0.96      0.97     14696
weighted avg       0.98      0.98      0.98     14696

## EfficientNetV2-S
Train Accuracy: 98.10%
Val Accuracy: 97.92%
Best Validation Accuracy: 97.95%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.99      0.99      0.99      2940
  Sayur_Buah       0.98      0.99      0.98      7839
 Sayur_Bunga       0.96      0.95      0.96      1959
  Sayur_Daun       0.96      0.95      0.95       979
Sayur_Polong       0.97      0.96      0.96       979

    accuracy                           0.98     14696
   macro avg       0.97      0.97      0.97     14696
weighted avg       0.98      0.98      0.98     14696

# Split Train 40%
## MLP
Train Accuracy: 97.32%
Val Accuracy: 98.57%
Best Validation Accuracy: 98.60%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.99      0.99      0.99      2520
  Sayur_Buah       0.99      0.99      0.99      6720
 Sayur_Bunga       0.98      0.98      0.98      1680
  Sayur_Daun       0.97      0.96      0.96       840
Sayur_Polong       0.99      0.98      0.98       840

    accuracy                           0.99     12600
   macro avg       0.98      0.98      0.98     12600
weighted avg       0.99      0.99      0.99     12600

## SVM
Train Accuracy: 99.33%
Val Accuracy:   98.22%  

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.99      0.99      0.99      2520
  Sayur_Buah       0.98      0.99      0.99      6720
 Sayur_Bunga       0.98      0.97      0.97      1680
  Sayur_Daun       0.98      0.91      0.94       840
Sayur_Polong       0.98      0.98      0.98       840

    accuracy                           0.98     12600
   macro avg       0.98      0.97      0.97     12600
weighted avg       0.98      0.98      0.98     12600

## EfficientNetV2-S
Train Accuracy: 98.81%
Val Accuracy: 98.52%
Best Validation Accuracy: 98.55%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      1.00      1.00      2520
  Sayur_Buah       0.99      0.99      0.99      6720
 Sayur_Bunga       0.97      0.97      0.97      1680
  Sayur_Daun       0.96      0.96      0.96       840
Sayur_Polong       0.97      0.99      0.98       840

    accuracy                           0.99     12600
   macro avg       0.98      0.98      0.98     12600
weighted avg       0.99      0.99      0.99     12600

# Split Train 50%
## MLP
Train Accuracy: 96.72%
Val Accuracy: 98.50%
Best Validation Accuracy: 98.65%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.99      0.99      0.99      2100
  Sayur_Buah       0.99      0.99      0.99      5600
 Sayur_Bunga       0.98      0.97      0.97      1400
  Sayur_Daun       0.97      0.96      0.97       700
Sayur_Polong       0.99      0.97      0.98       700

    accuracy                           0.98     10500
   macro avg       0.98      0.98      0.98     10500
weighted avg       0.98      0.98      0.98     10500

## SVM
Train Accuracy: 99.31%
Val Accuracy:   98.65%  

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      0.99      0.99      2100
  Sayur_Buah       0.99      0.99      0.99      5600
 Sayur_Bunga       0.98      0.97      0.98      1400
  Sayur_Daun       0.98      0.94      0.96       700
Sayur_Polong       0.99      0.99      0.99       700

    accuracy                           0.99     10500
   macro avg       0.99      0.98      0.98     10500
weighted avg       0.99      0.99      0.99     10500

## EfficientNetV2-S
Train Accuracy: 98.98%
Val Accuracy: 98.66%
Best Validation Accuracy: 98.75%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.99      1.00      1.00      2100
  Sayur_Buah       0.99      0.99      0.99      5600
 Sayur_Bunga       0.97      0.98      0.98      1400
  Sayur_Daun       0.98      0.96      0.97       700
Sayur_Polong       0.95      0.99      0.97       700

    accuracy                           0.99     10500
   macro avg       0.98      0.98      0.98     10500
weighted avg       0.99      0.99      0.99     10500

# Split Train 60%
## MLP
Train Accuracy: 97.90%
Val Accuracy: 98.90%
Best Validation Accuracy: 98.92%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      1.00      1.00      1680
  Sayur_Buah       0.99      0.99      0.99      4480
 Sayur_Bunga       0.98      0.98      0.98      1120
  Sayur_Daun       0.99      0.96      0.97       560
Sayur_Polong       0.99      0.98      0.99       560

    accuracy                           0.99      8400
   macro avg       0.99      0.98      0.98      8400
weighted avg       0.99      0.99      0.99      8400

## SVM
Train Accuracy: 99.42%
Val Accuracy:   98.58%  

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      1.00      1.00      1680
  Sayur_Buah       0.98      0.99      0.99      4480
 Sayur_Bunga       0.97      0.97      0.97      1120
  Sayur_Daun       0.99      0.95      0.97       560
Sayur_Polong       0.99      0.97      0.98       560

    accuracy                           0.99      8400
   macro avg       0.99      0.98      0.98      8400
weighted avg       0.99      0.99      0.99      8400

## EfficientNetV2-S
Train Accuracy: 98.76%
Val Accuracy: 98.61%
Best Validation Accuracy: 98.64%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       0.99      1.00      1.00      1680
  Sayur_Buah       0.99      0.99      0.99      4480
 Sayur_Bunga       0.97      0.97      0.97      1120
  Sayur_Daun       0.98      0.95      0.97       560
Sayur_Polong       0.99      0.98      0.98       560

    accuracy                           0.99      8400
   macro avg       0.98      0.98      0.98      8400
weighted avg       0.99      0.99      0.99      8400

# Split Train 70%

## MLP
Train Accuracy: 98.48%
Val Accuracy: 99.25%
Best Validation Accuracy: 99.35%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      1.00      1.00      1260
  Sayur_Buah       0.99      1.00      0.99      3360
 Sayur_Bunga       0.99      0.98      0.98       840
  Sayur_Daun       0.99      0.97      0.98       420
Sayur_Polong       1.00      0.99      0.99       420

    accuracy                           0.99      6300
   macro avg       0.99      0.99      0.99      6300
weighted avg       0.99      0.99      0.99      6300

## SVM
Train Accuracy: 99.39%
Val Accuracy:   98.98%  

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      1.00      1.00      1260
  Sayur_Buah       0.99      1.00      0.99      3360
 Sayur_Bunga       0.98      0.98      0.98       840
  Sayur_Daun       1.00      0.95      0.97       420
Sayur_Polong       1.00      0.98      0.99       420

    accuracy                           0.99      6300
   macro avg       0.99      0.98      0.99      6300
weighted avg       0.99      0.99      0.99      6300

## EfficientNetV2-S
Train Accuracy: 99.15%
Val Accuracy: 99.00%
Best Validation Accuracy: 99.00%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      1.00      1.00      1260
  Sayur_Buah       0.99      0.99      0.99      3360
 Sayur_Bunga       0.99      0.98      0.98       840
  Sayur_Daun       0.97      0.98      0.98       420
Sayur_Polong       0.98      0.98      0.98       420

    accuracy                           0.99      6300
   macro avg       0.99      0.99      0.99      6300
weighted avg       0.99      0.99      0.99      6300

# Split Train 80%
## MLP
Train Accuracy: 98.55%
Val Accuracy: 99.26%
Best Validation Accuracy: 99.36%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      1.00      1.00       840
  Sayur_Buah       0.99      0.99      0.99      2240
 Sayur_Bunga       0.98      0.99      0.98       560
  Sayur_Daun       0.99      0.97      0.98       280
Sayur_Polong       1.00      0.99      0.99       280

    accuracy                           0.99      4200
   macro avg       0.99      0.99      0.99      4200
weighted avg       0.99      0.99      0.99      4200

## SVM
Train Accuracy: 99.47%
Val Accuracy:   99.07% 

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      1.00      1.00       840
  Sayur_Buah       0.99      0.99      0.99      2240
 Sayur_Bunga       0.98      0.99      0.98       560
  Sayur_Daun       0.99      0.96      0.97       280
Sayur_Polong       1.00      0.98      0.99       280

    accuracy                           0.99      4200
   macro avg       0.99      0.98      0.99      4200
weighted avg       0.99      0.99      0.99      4200

## EfficientNetV2-S
Train Accuracy: 99.34%
Val Accuracy: 99.38%
Best Validation Accuracy: 99.38%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      1.00      1.00       840
  Sayur_Buah       1.00      1.00      1.00      2240
 Sayur_Bunga       0.99      0.99      0.99       560
  Sayur_Daun       0.99      0.98      0.99       280
Sayur_Polong       0.99      0.99      0.99       280

    accuracy                           0.99      4200
   macro avg       0.99      0.99      0.99      4200
weighted avg       0.99      0.99      0.99      4200

# Split Train 90%
## MLP
Train Accuracy: 98.88%
Val Accuracy: 99.33%
Best Validation Accuracy: 99.33%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      1.00      1.00       420
  Sayur_Buah       0.99      1.00      1.00      1120
 Sayur_Bunga       1.00      0.97      0.99       280
  Sayur_Daun       0.97      0.99      0.98       140
Sayur_Polong       0.99      0.98      0.99       140

    accuracy                           0.99      2100
   macro avg       0.99      0.99      0.99      2100
weighted avg       0.99      0.99      0.99      2100

## SVM
Train Accuracy: 99.49%
Val Accuracy:   98.76%   

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      1.00      1.00       420
  Sayur_Buah       0.98      0.99      0.99      1120
 Sayur_Bunga       0.99      0.97      0.98       280
  Sayur_Daun       0.98      0.94      0.96       140
Sayur_Polong       0.99      0.98      0.98       140

    accuracy                           0.99      2100
   macro avg       0.99      0.98      0.98      2100
weighted avg       0.99      0.99      0.99      2100

## EfficientNetV2-S
Train Accuracy: 99.69%
Val Accuracy: 99.43%
Best Validation Accuracy: 99.48%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      1.00      1.00       420
  Sayur_Buah       0.99      1.00      1.00      1120
 Sayur_Bunga       0.99      0.98      0.99       280
  Sayur_Daun       1.00      0.99      1.00       140
Sayur_Polong       0.99      1.00      1.00       140

    accuracy                           0.99      2100
   macro avg       0.99      0.99      0.99      2100
weighted avg       0.99      0.99      0.99      2100

# Split Train 95%
## MLP
Train Accuracy: 98.78%
Val Accuracy: 99.52%
Best Validation Accuracy: 99.71%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      1.00      1.00       210
  Sayur_Buah       1.00      0.99      1.00       560
 Sayur_Bunga       0.98      0.99      0.99       140
  Sayur_Daun       1.00      1.00      1.00        70
Sayur_Polong       1.00      1.00      1.00        70

    accuracy                           1.00      1050
   macro avg       0.99      1.00      1.00      1050
weighted avg       1.00      1.00      1.00      1050

## SVM
Train Accuracy: 99.50%
Val Accuracy:   99.52%  

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      1.00      1.00       210
  Sayur_Buah       0.99      1.00      1.00       560
 Sayur_Bunga       0.99      0.99      0.99       140
  Sayur_Daun       1.00      0.97      0.99        70
Sayur_Polong       1.00      1.00      1.00        70

    accuracy                           1.00      1050
   macro avg       1.00      0.99      0.99      1050
weighted avg       1.00      1.00      1.00      1050

## EfficientNetV2-S
Train Accuracy: 99.82%
Val Accuracy: 100.00%
Best Validation Accuracy: 100.00%

============================================================
Classification Report
============================================================
              precision    recall  f1-score   support

  Sayur_Akar       1.00      1.00      1.00       210
  Sayur_Buah       1.00      1.00      1.00       560
 Sayur_Bunga       1.00      1.00      1.00       140
  Sayur_Daun       1.00      1.00      1.00        70
Sayur_Polong       1.00      1.00      1.00        70

    accuracy                           1.00      1050
   macro avg       1.00      1.00      1.00      1050
weighted avg       1.00      1.00      1.00      1050