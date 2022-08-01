# Credit_Risk_Analysis
Using Algorithms like: randomOverSample, SMOTE, ClusterCentroids, SMOTEEN

# Overview of the analysis:

For this Challenge we analyze different kind of algorithms in order to see the difference between their results, so it is possible to analyze their outputs by printing final reports retrieving thier optimal values each one, with this methos we can know their `accuracy`, `precision`, and `sensitivity`, we can also see others values like `F1` which involves precision and sensitivity at the same time, precision is a measure of how reliable a positive classification is, while sensitivity is a measure of how many positive values were actually correctly diagnosed, and `support` values referes to the actual ocurrences of the class in the dataset were taken, so we can have a better landscape of the information.

In ythe next images some values are mention as part of the anlysis for each method mentioned, for all methods there are two classes: low_risk and high_risk, these values refer to the possibility for a good loan and the opposite, those values with the high risk, are those who present not good evaluation for a loan request.


# Results:

* **Naive Random Oversampling** ***balanced accuracy score:*** 0.6398437216722869 or 63%.

For this first image the accuracy is low, we can say that just a small part more than 50% of the data were correctly analyzed, and comparing with the report the `precision` shows a 100% good for the class low risk, the `sensitivity` retrieved indicates almost 50% for each class, but f1 values supports a little to precision due is it higher than 80%. 

![Naive_Random_Oversampling](/ResourcesP/Naive Random Oversampling.png)

* **SMOTE Oversampling** ***balanced accuracy score:*** 0.6216172933512213 or 62%.

There is not su much so say about the **SMOTE** method, we can compare with the Naive Random Oversampling method, we can realized their values are almost the same, there is a small diference in the "rec" or "sensitivity" column of 0.3% and in f1 values, there is a difference of 0.3%, and we can see the number of values for each class taken were the same ones.

![SMOTE_Oversampling](/ResourcesP/SMOTE Oversampling.png)

* **Undersampling using ClusterCentroids** ***balance accuracy score:*** 0.6216172933512213 or 62%.

This method shows a minor accuracy than the previous ones, the precision is the same than the other before, but there is a slight difference in the  recall or sensitivity values, where the risk for the high risk class increase a little bit, the f1 values is just a little over 50 %, for the low_risk class, showing the non- confidence while applying this method.

![Cluster_Centroids](/ResourcesP/Cluster_Centroids.png)

* **SMOTEENN** Combination (Over and Under) Sampling, ***balace accuracy score:*** 0.6357786318898034 or 63%.

In this method the accuracy is 0.6357786318898034 or 63% we can say, giving us uncertainty in using the method, the precision is good, however for each class, the sensitivity is almost the same for the classes, the f1 values retrieves is higher than the three past methods wit more than 70%, we can deduct according the differences in values is non a good choice to evaluate our data.

![Smoteen](/ResourcesP/Combination_OverandUnder_Sampling.png)

**Ensemble Learners**
* **Balanced Random Forest Classifier** ***balace accuracy score:**

![Balance_Random_Forest_Classifier](/ResourcesP/Balanced_Random_Forest_Classifier.png)

* **Easy Ensemble AdaBoost Classifier** ***balace accuracy score:** 0.9896541702993316 or 98%.

![Easy_Ensemble_AdaBoost_Classifier](/ResourcesP/EasyEnsembleAdaBoostClassifier.png)

# Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
