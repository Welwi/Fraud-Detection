# IEEE-CIS Fraud Detection
# By: Edna Fernandes

Project Goals/Overview
The dataset for this project was obtained from https://www.kaggle.com/c/ieee-fraud-detection/data.
The purpose of the project is to improve the fraud prevention system in order for businesses to reduce their losses due to fraud and increase their revenues, and also to improve the customer experience.


The final presentation can be found in the file 'Final_Presentation.pdf'.

README Summary
In this README I am going to explain the approach taken to prepare the data for the baseline model and the model technique used.

Data Cleaning
The original training dataset is found on 'train_transaction.csv', 'train_identity.csv'. The test set can be found on 'test_transaction.csv' and 'test_identity.csv'. 

For the base model, due to computer capacity, I decided to use only the original features (I am not using the features engineered by Vesta).

I am also imputing all the missing values with 'most_frequent'.

I have done some exploratory data analysis and some of the insights can be found on the presentation slides.


Models
For the binary model I used logistic regression. 
The metric that is being used is AUC, which was specified by Vesta.
This base model has a score of 76%.


Next steps
I am going to model using XGBoost.
