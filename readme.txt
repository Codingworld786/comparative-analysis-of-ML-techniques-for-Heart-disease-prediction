pipeline of project:

First, we loaded the data named ‘heart.csv’.
Then we standardize the numeric features using StandardScaler() function.
We have used 6 ML algorithms for comparison:
Logistic Regression
KNN
Random Forest
SVM
Decision Tree
XG-Boost Classifier
Result
In the context of heart disease prediction, a false negative occurs when the model fails to identify a person with heart disease as having the condition, which can be critical as it means a potential misdiagnosis and the person might not receive appropriate medical attention.
Recall, also known as sensitivity or true positive rate, measures the ability of the model to correctly identify positive cases (cases of heart disease) out of all actual positive cases.
So, we will be selecting the best model on the basis of the highest recall value.
For both 5-fold cross-validation and 10-fold cross-validation, SVM is giving the highest recall value.
SVM gives a recall of 90.27% with 10-fold cross-validation and a recall of 88.75% with 5-fold cross-validation. So, in our study, we find that the SVM method is best for this project.
