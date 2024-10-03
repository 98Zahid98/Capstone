# Capstone
My capstone project
# My first capstone
#### Background:
This dataset shows the Online Shoppers Purchasing Intention.

#### Objective:
Use machine learning methods to predict Online Shoppers Purchasing Intention based on a specific campaign, special day, user profile, or period.

#### Provenance / Origin of data:
Dataset downloaded from kaggle: https://www.kaggle.com/datasets/imakash3011/online-shoppers-purchasing-intention-dataset?resource=download ,
Dataset has 12330 records with 18 columns

[Screenshot of dashboard](https://i.imgur.com/Pi2AVaR.png)

[Link to dataset](https://www.kaggle.com/datasets/imakash3011/online-shoppers-purchasing-intention-dataset?resource=download)

#### Description of Dataset:
The dataset consists of feature vectors belonging to 12,330 sessions.The dataset was formed so that each session would belong to a different user in a 1-year period to avoid any tendency to a specific campaign, special day, user
profile, or period.

#### General Observations:
There are no missing value in any row/column. Hence, no need to treat the missing values.
Imbalanced dataset.  The minority class "0" (Non Returning Visitor) is 5.9 times smaller than the majority class "1" (Returning Visitor).
Shocking to find returning visitors have higher bounce rates, exit rates and lower page values as compared to new visitors. Probably more familiar with the website, know what they want
Noticed from heatmap exit rates & bounce rates have the highest correlation

#### Insights:
SMOTE was applied with the intention to balance the dataset, with hope of better accuracy.  However, after applying SMOTE, accuracy of the model dropped from 0.86 to 0.67.  
This could be due to the new synthetic samples being generated in overlapping areas.
Decision Tree (with K-fold cross validation) algorithm is the best algorithm for our model with the highest accuracy around percent

#### What I have learned:
Choosing the column to predict based on the problem definition
Checking the data types of columns in the dataset to see what interactive charts to use for EDA
Cross-Validation to evaluate the performance of models, hyperparameter Tuning to improve performance

#### Connect with Me!:
Like my work?Send me a DM on
[Link to Linkedin](https://www.linkedin.com/in/zahid-salam-b79290137/)

