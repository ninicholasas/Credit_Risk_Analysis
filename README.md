# Credit_Risk_Analysis

## Overview of Analysis


## Results
### Naive Random Oversampling
* Balanced Accuracy Score: 0.6511924140262483
* Precision Score;
  * high_risk: 0.01
  * low_risk : 1.00
  * avg/total: 0.99
* Recall Score;
  * high_risk: 0.74
  * low_risk : 0.56
  * avg/total: 0.56

---

### SMOTE Oversampling
* Balanced Accuracy Score: 0.6548711319915902
* Precision Score;
  * high_risk: 0.01
  * low_risk : 1.00 
  * avg/total: 0.99
* Recall Score;
  * high_risk: 0.62
  * low_risk : 0.69
  * avg/total: 0.69

---

### Undersampling
* Balanced Accuracy Score: 0.5442369453268994
* Precision Score;
  * high_risk: 0.01
  * low_risk : 1.00
  * avg/total: 0.99
* Recall Score;
  * high_risk: 0.69
  * low_risk : 0.40
  * avg/total: 0.4

---

### Combination (Over and Under) Sampling
* Balanced Accuracy Score: 0.6381140072613435
* Precision Score;
  * high_risk: 0.01
  * low_risk : 1.00
  * avg/total: 0.99
* Recall Score;
  * high_risk: 0.70
  * low_risk : 0.57
  * avg/total: 0.57

---

### Balanced Random Forest Classifier
* Balanced Accuracy Score: 0.5
* Precision Score;
  * high_risk: 0.01
  * low_risk : 0.00
  * avg/total: 0.00
* Recall Score;
  * high_risk: 1.00
  * low_risk : 0.00
  * avg/total: 0.01

---

### Easy Ensemble AdaBoost Classifier
* Balanced Accuracy Score: 0.931601605553446
* Precision Score;
  * high_risk: 0.09
  * low_risk : 1.00
  * avg/total: 0.99
* Recall Score;
  * high_risk: 0.92
  * low_risk : 0.94
  * avg/total: 0.94


## Summary
Overall all the classifiers seem to have a same accuaacy other than the Easy Ensemble AdaBoost Classifier. 
