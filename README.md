# Fraud-transaction-detection
This project deals with modeling past credit card transactions with the data of the ones that turned out to be fraud. It is then used to identify whether a new transaction is fraudulent or not. Aim of this project here is to detect 100% of the fraudulent transactions while minimizing the incorrect fraud classifications.
# Data-collection
Data has been collected from https://www.kaggle.com/mlg-ulb/creditcardfraud
# Data-pre-processing
Data has been understood and and analysed thoroughly and necessary pre-processing has been done and the data has been standardised using Standardscaler. There were no missing data in the data set to be assigned with. 
Correlation matrix has been used to understand the correlation between the variables.
# Splitting the data
Data has been split using train test split accordingly.
75% of the data has been assigned for training purpose and the rest for splitting.
# Training the model
Model has been trained using RandomForest classifier as it produces the highest accuracy when compared to other models.
Data alloted for training purpose has been utilized to train the model.
# Analysis and visualization
The obtained output is then analysed using confusion matrix and the following are obtained:
1. Accuracy
2. Error
3. Specificity
4. Sensitivity
5. Precision
6. Recall 
7. F1 score
Since the data is unbalanced AUPRC curves are also used to detect the accuracy.
# Random forest tree visualisation
Finally a Randomforesttree with the data has been displayed for the understanding purpose.
