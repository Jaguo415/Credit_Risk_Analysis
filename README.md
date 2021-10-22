# Credit_Risk_Analysis


## Overview
For this Challenge, we will be using python to build and apply several ml models to predict credit risk. We will be following the following procedure.

* Oversample the Data using the RandomoverSampler and SMOTE
* Undersample the data using ClusterCentriods
* Using the SMOTEENN model and apply a combinator approach, over and under sampling
* compare two ml models that help reduce bias, BalanceRandomForestClassifier and EasyEnsembleClassifier

Based on the performance of these models, we should use the results to help predict risk. 




## Resources

* Data: LoanStat_2019Q1.CSV
* Software: Python 3.7.9, and Jupyter Notebook

## Models

### RandomOverSampler

<img width="722" alt="Screen Shot 2021-10-19 at 6 06 42 PM" src="https://user-images.githubusercontent.com/83923903/138011692-9b1cbdd7-1e8d-4fc1-a7c2-be12af188687.png">

* Balance Accuracy score is 63.9%
* There is a lower number of applicants in High_risk, so its precision is 1% and about 59% sensitivity
* There is a higher number of applicants in the low_risk, so its precision is about 99% with a 69% sensativity.

### SMOTE

<img width="746" alt="Screen Shot 2021-10-19 at 6 14 35 PM" src="https://user-images.githubusercontent.com/83923903/138011750-a970baef-e09d-40a2-8755-6834c479b7b5.png">

* Balance Accuracy score is 62%
* There is a lower number of applicants in high_risk so its precision is about 1% with a 63% sensativity.
* There is a higher number of applicants in low_risk so its precisiion is about 100% and with a 69% sensativity.

### ClusteredCentroid

<img width="750" alt="Screen Shot 2021-10-19 at 6 16 00 PM" src="https://user-images.githubusercontent.com/83923903/138011863-b062ff24-c16b-4cb3-a4d3-dfa1827b0122.png">

* Balance accuracy score is 52%
* There is a lower number of applicants in high_risk so its precision is about 1% with a 57% sensativity.
* There is a higher number of applicants in low_risk so its precisiion is about 100% and with a 46% sensativity.

### SMOTEENN

<img width="751" alt="Screen Shot 2021-10-19 at 6 17 02 PM" src="https://user-images.githubusercontent.com/83923903/138011916-1f6379af-f889-43a9-bf68-04be030debd4.png">

* Balance accuracy score is 61%
* There is a lower number of applicants in high_risk so its precision is about 1% with a 68% sensativity.
* There is a higher number of applicants in low_risk so its precisiion is about 100% and with a 54% sensativity.

### BalancedRandomForestClassifier

<img width="747" alt="Screen Shot 2021-10-19 at 6 17 38 PM" src="https://user-images.githubusercontent.com/83923903/138011957-29e144d6-f709-4c63-bfed-dace37846c6e.png">

* Balance accuracy score is 78%
* There is a lower number of applicants in high_risk so its precision is about 4% with a 67% sensativity.
* There is a higher number of applicants in low_risk so its precisiion is about 100% and with a 91% sensativity.

### EasyEnsembleClassiifier

<img width="743" alt="Screen Shot 2021-10-19 at 6 18 24 PM" src="https://user-images.githubusercontent.com/83923903/138012034-98788d65-6cea-4428-8a80-01fd3d815192.png">
* Balance accuracy score is 61%
* There is a lower number of applicants in high_risk so its precision is about 7% with a 91% sensativity.
* There is a higher number of applicants in low_risk so its precisiion is about 100% and with a 94% sensativity.


