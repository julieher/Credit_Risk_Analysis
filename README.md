# Credit_Risk_Analysis
Mod 17

# Overview: 
The purpose of this project is to use different techniques to train and evaluate models with **unbalanced classes** in order to predict credit risk. The different algorithms used for oversampling data were `RandomOverSampler` and `SMOTE`; for data undersampling, we used `ClusterCentroids`.

Then, we tested a two-step process for oversampling and undersampling data using `SMOTEENN` algorithm. Lastly, `BalancedRandomForestClassifier` and `EasyEnsembleClassifier` models were used to reduce bias and predict credit risk.

# Results: 
Below are the accuracy scores, confusion matrices, and classification reports for each of the six machine learning models.

### 1. Random Oversampling
![](/Images/1_randomOver.png)

### 2. SMOTE
![](/Images/2_SMOTE.png)

### 3. Cluster Centroids
![](/Images/3_ClusterCentroids.png)

### 4. SMOTEENN
![](/Images/4_SMOTEENN.png)

**Machine Learning Models:**

### 5. Balanced Random Forest Classifier
![](/Images/5_BalancedRandomForest.png)

### 6. Easy Ensemble Classifier
![](/Images/6_EasyEnsemble.png)

# Summary:
From the six models, Easy Ensemble Classifier is the most efficient determining credit risk. It has the highest recall score as well as the highest balanced accuracy score. 

# Resources:
[EasyEnsembleClassifier](https://imbalanced-learn.org/stable/references/generated/imblearn.ensemble.EasyEnsembleClassifier.html)

[BalancedRandomForestClassifier](https://imbalanced-learn.org/stable/references/generated/imblearn.ensemble.BalancedRandomForestClassifier.html)

[get_dummies](https://pandas.pydata.org/docs/reference/api/pandas.get_dummies.html)

