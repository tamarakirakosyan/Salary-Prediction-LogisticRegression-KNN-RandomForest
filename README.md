# Salary-Prediction-LogisticRegression-KNN-RandomForest
Predicting whether salary is above or below 50k per year.

# Data
![image](https://github.com/tamarakirakosyan/Salary-Prediction-LogisticRegression-KNN-RandomForest/assets/46844022/c8d408fe-50a8-412e-97c2-ee7ca6300e3e)

# Results and Model Evaluation
Our Goal is to predict whether salary will be above or below 50k per year.
For prediction of salary I used three machine learning models: Logistic Regression, KNN and Random Forest. Random Forest model gives the best results. Also I did GridSearch to find best hyperparameters for the priction.

We get the following final resutls on test data:
**Precision:** Precision on the testing data is 86% which means that the amount of false positives is low.
**Recall:** Recal on the testing data is 87% which means that the model accurately predicts 87% percent of true positives.
**F1 Score:** F1 Score on the testing data is 86% which means overall accuracy of the model is 86%.

As the training and testing data metrics do not differ a lot, we can say that we don't have a risk of overfitting.
