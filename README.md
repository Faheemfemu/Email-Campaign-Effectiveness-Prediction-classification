# Email-Campaign-Effectiveness-Prediction-classification
# Project Summary -
The goal of this project is to create a machine learning model that can characterize and track emails sent through Gmail-based email marketing campaigns. This model will be used by small to medium business owners who are looking to improve the effectiveness of their email marketing efforts and increase customer retention.Using this data, we will train a machine learning model to predict whether an email is likely to be read, ignored, or acknowledged by the reader. This model will be able to analyze new emails and provide a prediction of how they are likely to be received by the reader.

To evaluate the performance of the model, we will split our data into a training set and a testing set. We will use the training set to fit the model and the testing set to evaluate its performance. We will use a variety of metrics, such as precision, recall, and F1 score, to assess the model's accuracy and effectiveness.

Overall, this project aims to provide small to medium business owners with a powerful tool for improving the effectiveness of their email marketing campaigns. By using machine learning to characterize and track emails, they will be able to make more informed decisions and increase the chances of success for their marketing efforts.
# Problem Statement
Most of the small to medium business owners are making effective use of Gmail-based Email marketing Strategies for offline targeting of converting their prospective customers into leads so that they stay with them in Business. The main objective is to create a machine learning model to characterize the mail and track the mail that is ignored; read; acknowledged by the reader.
# Approach: 
The approach followed here is to first check the sanctity of the data and then understand the features involved. The events followed were in our approach:

Understanding the Data

Data cleaning and preprocessing-

finding null values and imputing them

with appropriate values.

Exploratory data analysis- of
categorical and continuous variables against our target variable.

Data manipulation- feature selection
and engineering, handling multicollinearity with the help of VIF scores, feature scaling, and encoding.

Handling Class Imbalance- our dataset
was highly imbalance with an 80% majority, strategy was to undersampling and oversampling with SMOTE on the train sets only so that our test set remains unknown to the models, we also applied Tomek link which is hybridisation of oversampling and undersampling ,so that we can compare our results

Modeling- worked on an evaluation
code which was frequently used to evaluate the same models on undersampled , oversampled SMOTE and Tomeklink data in one go, decision trees, random forest, KNN, and XGB, Gradient Boosting, catboost and SVM were run to evaluate the results and then concluded on the basis of model performance and enhancedits performance using Hypertuning the model parameters.We used RandomisedSearchCV technique.
