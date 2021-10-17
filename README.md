# Anomaly Detection - Credit Card Fraud Detection

Anomaly detection is a technique for finding an unusual point or pattern in a given set.

The term anomaly is also referred to as outlier. Earlier, the data mining researchers were focused on other techniques like classification and clustering. Outlier are found as a part of data cleansing process.

However, view underwent a change in 2000 when researchers found detection of abnormal things can help solving the real world problems seen in damage detection, fraud detection, detection of abnormal health condition and intrusion detection.

## Table of Contents

- [Goal](#goal)
- [Workflow](#workflow)
- [Required Packages](#require)


## Goal <a name = "goal"></a>

In this notebook we'll be using multiple machine learning algorithms to detect and classify suspicious credit card transactions.

## Data <a name = "dataset"></a>

The dataset contains transactions made by credit cards in September 2013 by European cardholders.

The dataset is highly unbalanced.

It contains only numerical input variables which are the result of a PCA transformation. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. 


## Workflow <a name = "workflow"></a>

- Basic EDA
- Feature scaling
- Modeling (Imbalanced Dataset)
    - SVC
    - KNearest Neighbours
    - Random Forest
    - Isolation Forest
    - Local Outlier Factor
- Modeling (Over Sampling)
    - SVC
    - KNearest Neighbours
    - Random Forest
    - Isolation Forest
    - Local Outlier Factor
- Modeling (Under Sampling)
    - SVC
    - KNearest Neighbours
    - Random Forest
    - Isolation Forest
    - Local Outlier Factor
    - Cross Validation
        - Random Forest
- Conclusion

## Result
Random Forest + Under sampling is giving us good accuracy.

But it can also be a case of over-fitting.

To validate this hypothesis, we applied cross validation and confirmed, there is no over-fitting.

## Required Packages <a name = "require"></a>

- numpy
- pandas
- sklearn
- easypreprocessing 
- seaborn

