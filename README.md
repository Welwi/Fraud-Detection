# IEEE-CIS Fraud Detection
# By: Edna Fernandes

## Project Goals/Overview
The dataset for this project was obtained from https://www.kaggle.com/c/ieee-fraud-detection/data.
The purpose of the project is to improve the fraud prevention system in order for businesses to reduce their losses due to fraud and increase their revenues, and also to improve the customer experience.


The final presentation can be found in the file 'Final_Presentation.pdf'.

## README Summary
In this README I am going to explain the approach taken to prepare the data for the baseline model and the model technique used.

## Data Cleaning
The original training and test sets can be found on the kaggle link provided above. Due to the big size of the dataset, I was not able to post it on my github. 

I have done some exploratory data analysis and some of the insights can be found on the presentation slides.


## Models
The data provided had over 300 features. Using the SelectFromModel from scikit-learn, I was able to reduce this number to the 100 most meaningful features.

Once I had all my features selected, I built a final model using the imbalanced XGBoost. 

I achieved a score of 90% on the kaggle leaderboard.


