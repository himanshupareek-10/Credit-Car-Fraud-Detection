# Credit-Car-Fraud-Detection
## Problem statement 

The problem statement chosen for this project is to predict fraudulent credit card transactions with the help of machine learning model.

In this project, we will analyse customer-level data which has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group. 

The dataset is taken from the [Kaggle Website](https://www.kaggle.com/mlg-ulb/creditcardfraud) website and it has a total of 2,84,807 transactions, out of which 492 are fraudulent.


## Data Description

The dataset can be download using this [link](https://www.kaggle.com/mlg-ulb/creditcardfraud)

The data set includes credit card transactions made by European cardholders over a period of two days in September 2013. Out of a total of 2,84,807 transactions, 492 were fraudulent. This data set is highly unbalanced, with the positive class (frauds) accounting for 0.172% of the total transactions. The data set has also been modified with Principal Component Analysis (PCA) to maintain confidentiality. Apart from ‘time’ and ‘amount’, all the other features (V1, V2, V3, up to V28) are the principal components obtained using PCA. The feature 'time' contains the seconds elapsed between the first transaction in the data set and the subsequent transactions. The feature 'amount' is the transaction amount. The feature 'class' represents class labelling, and it takes the value 1 in cases of fraud and 0 in others.


## Project Pipeline

The project pipeline can be briefly summarized in the following four steps:

- **Data Understanding:** Here, we need to load the data and understand the features present in it.
- **Exploratory data analytics (EDA):** Normally, in this step, we need to perform univariate and bivariate analyses of the data, followed by feature transformations, if necessary.
- **Train/Test Split:** Now we are familiar with the train/test split, which we can perform in order to check the performance of our models with unseen data. 
- **Model-Building/Hyperparameter Tuning:** This is the final step at which we can try Logistic Regression.
- **Model Evaluation:** We need to evaluate the models using appropriate evaluation metrics. Note that since the data is imbalanced it is is more important to identify which are fraudulent transactions accurately than the non-fraudulent. We need to choose an appropriate evaluation metric which reflects this business goal.
