# Project Title: Predicting Customer Churn Using Machine Learning in banking industry

This research investigates the effectiveness of various machine learning models—Logistic 
Regression (LR), Decision Tree (DT), Random Forest (RF), K-Nearest Neighbors (KNN), Support 
Vector Machine (SVM), and Extreme Gradient Boosting (XGB)—in predicting customer churn 
within the banking sector. 

The study aims to identify the model that provides the best predictive 
accuracy and interpretability, considering both the prediction of churn and the reasons behind it. 


A comprehensive dataset from Kaggle's “Bank Customer Churn Prediction in 2018” was 
employed, comprising demographic, account, and transactional features. The methodology 
included feature engineering to create interaction, temporal, and behavioral features, which 
enhanced model performance. 

Additionally, the study incorporated cost-sensitive learning techniques to address class imbalance, 
emphasizing the reduction of false negatives through an asymmetric cost matrix. This approach 
was particularly vital for optimizing financial outcomes, as misclassifying a churner as a non
churner incurs significant costs in the banking context. 

The analysis concluded that ensemble 
models, specifically RF and XGB, outperformed other models in both predictive accuracy and cost 
efficiency. The Shapley Additive Explanations (SHAP) analysis provided insights into the most 
influential features affecting churn, with "IsActiveMember" and "NumOfProducts" being notable 
contributors. 

The findings underscore the importance of integrating machine learning and cost
sensitive strategies to enhance customer retention efforts in the banking industry, providing a 
robust framework for future applications and research.
