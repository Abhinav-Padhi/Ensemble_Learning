#Devsoc core assignment for AI/ML vertical. BMI classifier
##This is a ML project for exploring ensemble learning techniques

The data was preprocessed by using StandardScaler on all columns of float64 data type.
Furthermore, all object data type columns are either label encoded or binary encoded.

I chose the baseline model to be Decision Tree (approximately 84% accuracy).

1st Ensemble learning technique is bagging which uses Random Forests to make redictions (approximately 90% accuracy).

2nd Ensemble learning technique is Boosting wherein I have used AdaBoost (approximately 63% accuracy),Gradient Boosting (approximately 90% accuracy) and XGBoost (approximately 89% accuracy).

3rd  Ensemble learning technique is Stacking where I have used Naive Bayes, Random Forest and SVM as base models and XGBoost as meta model(approximately 90% accuracy).

Next is Blending in which I first split data into 70% for train and 30% holdout, holdout data was further split 50-50 into X_val and X_test.

After that there are voting models which use Naive Bayes,Random Forest and Logistic Regression
1) Hard Voting (approximately 76% accuracy)
2) Soft Voting (approximately 83% accuracy)
3) Weighted Voting (approximately 83% accuracy)

