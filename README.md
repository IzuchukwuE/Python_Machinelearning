# MYProjects
 -Improved Credit Card Fraud Detection Performance Using Ensembles in Machine Learning Algorithms

# Overview
-This is a readme detailing the process of cleaning and investigating prediction output using different algorithms on  Credit Card Fraud dataset. 
In this project, RandomForest, Decicsion tree, and autoencoder are compared against adaboost,catboost, and voterclasifer
-The purpose of this project is to improve credit card fraud prediction 

Timeframe of the study: 2015 - 2017
# Resources and tools used
- Dataset is gotten from Kaggle
# Data Transformation 
- Null value was removed
- heat map plotted to show correlation
- data visualized using  scatter plot. observation of  outliers.
- further transformed dataset using selectkbest 
- Smothe approach to reduce the imbalanced nature of the dataset. 
- standard scaler to scale the dataset
# TestTrain
- Dataset is split and trained using  logistic regression,
- dataset is tested and prediction occurs. 
- Various parameters like precision, f1-score, recall, specificity, sensitivity, accuracy, and MSE are used for comparative analysis
- The outcome of these parameters is compared between the different algorithms used to know which performed best
  # Result
-   Adaboost and Voting classifiers performed better than RandomForest and Decision Tree
# Conclusion
- With MSE smaller than 0.0011, both training and testing datasets achieved more than 99 percent accuracy.
- The end result proved that Adaboost and Voting classifiers showed improved accuracy than some other methods.
