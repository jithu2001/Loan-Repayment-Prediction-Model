E-Bike Loan Non-Payment Prediction using Random Forest Algorithm

Objective

In this project, we aim to build a Credit Risk Model to predict whether a client will fail to honor their loan repayment obligation for E-Bike purchases. We will be working with a dataset provided by one of the banks facing profit challenges due to non-payment incidents in their E-Bike financing division. The objective is to understand the factors contributing to a borrower's propensity to default on their loan and develop a model to predict the "Non-Payment" risk level for each client.

Dataset

The dataset consists of the following columns:
ID: Unique identifier for each record.
Default: The target variable indicating whether the client defaulted on their loan (1: Defaulted, 0: Not Defaulted).
The rest of the columns are used as features (X variables) to predict the default risk.

Approach

We have used the Random Forest algorithm for building the predictive model. Random Forest is an ensemble learning method that combines multiple decision trees to make more accurate predictions. It is well-suited for classification tasks like ours.
Additionally, we performed the following preprocessing steps:
Label Encoding: Converting categorical variables into numeric form for model training.
Normalization: Scaling numerical features to ensure they are on a similar scale and avoid dominance by one feature.

Feature Importance

Random Forest provides a feature importance score, which helps us understand the relative significance of each feature in predicting loan defaults. This analysis can guide the bank in identifying potential loan defaulters based on the client's attributes.

Evaluation Metric

For evaluating the performance of our Credit Risk Model, we have defined our custom evaluation metric based on our intuition. As loan default prediction is a highly imbalanced classification problem, accuracy alone may not be sufficient. Therefore, we will use a combination of precision, recall, and F1-score to measure the model's performance.
Feel free to explore the code and analysis provided in this repository to gain insights into the predictive model's results.
Please note that the dataset used here is for demonstration purposes only and does not contain real customer data.
 
Conclusion

By using the Random Forest algorithm, label encoding, normalization, and analyzing feature importance, we have developed a predictive Credit Risk Model to assist the bank in identifying potential loan defaulters for E-Bike purchases. The model's evaluation metrics provide insights into its performance, helping the bank make better-informed decisions and mitigate risks.
Please feel free to reach out if you have any questions or suggestions to improve the model.
