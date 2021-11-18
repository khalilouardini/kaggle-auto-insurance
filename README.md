# Kaggle Auto Insurance
This repository contains the code for the 2017 Kaggle Auto Insurance challenge. (https://www.kaggle.com/c/auto-insurance-fall-2017/)

## Setup
In your environment, run:
```
pip install - r requirements.txt
```

## Jupyter Notebook

The Jupyter Notebook contains all the steps of the solution and is divided in 4 main parts:
* Feature engineering and data exploration 
* Pre-Processing
* Models
* Predictions

## Results
The test predcitions for the 'TARGET_FLAG' and the pre-processed test set are in ```preprocessed_test_and_predictions.csv``` file.
We reach the best performance with a XGBoost Classifier. The final evaluation metrics on the 5-fold cross validation are.

* Accuracy = 0.79
* Precision = 0.67
* Recall = 0.65
* F1 score = 0.59


