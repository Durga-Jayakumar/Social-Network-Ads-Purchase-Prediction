## Social Network Ads Purchase Prediction

**Overview**

This project focuses on predicting whether a user will purchase a product based on demographic features such as age, estimated salary, and gender. Using a dataset of social network advertisements, the goal is to build a classification model that can accurately identify potential buyers. 

The project begins with data preprocessing, including handling missing values, encoding categorical variables, and feature scaling. A Logistic Regression model is first implemented as a baseline to understand the underlying patterns in the data and establish initial performance.
To improve results, a Random Forest Classifier is then applied, allowing the model to capture more complex, non-linear relationships between features. Model performance is evaluated using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.

The final model demonstrates improved accuracy and a stronger ability to identify buyers, highlighting the importance of selecting appropriate models based on the nature of the data.

**Data Set Information**

This dataset is referred from Kaggle Repository.

Kaggle source: https://www.kaggle.com/datasets/rakeshrau/social-network-ads/data

**Data Card**

  Shape : 400 Rows & 5 Columns

  Attributes :

*   User ID : Unique ID for each user
*   Gender : Male/Female
*   Age : 18 - 60
*   EstimatedSalary : 15.0k - 150k
*   Purchased : 0/1

