# Machine-Learning
#Project 1:
Heart disease classification model (Jupyter notebook);
processed.cleveland.data (dataset); Description(Imported data.
Identified and dealt with missing data.
Formatted the data for Decision Trees using One-Hot Encoding.
Built a Preliminary Decision Tree for Classification (Recall =79%).
Pruned the Decision Tree with Cost Complexity Pruning.
Built,Drew,Interpreted and Evaluated the final Decision Tree.
Recall= 85%, Precesion= 77.78%, Accuracy 82.67%, F1_score =0.8115.)
 
#Project 2:
House price prediction kaggle competition:
Train and test datasets were given. Cleaned both datasets and took care of null values using mean for numerical and mode for categorical data;
Drop the columns having more than 50% of null values;Combined testand train for one hot encoding and then split again;
Remove the house price column from the test data to form X_train and y_train dataframes; Used Xgboost regressor for training the data. Used the model to predict 
house prices in test dataset;Submitted the prediction file sample_submission2.csv on kaggle. Rank: 1745; Mean Squared Error: 0.14257

#Project 3:
Car Price Prediction:
No missing data found, model the data using one-hot encoding  for categorical features.
Deleted unwanted feature and derived a new feature from existing one.
Used Linear Regressor and found best random_state out of thousand random train-test split gives optimized r2_score. MAE: 0.889; MSE: 1.5; RMSE: 1.225,r2_score=0.937.
Used Random Forest Regressor model and pruned the model with RandomizedSearchCV to find best parameters. r2_score>0.97.

#Project 4:
Rainfall Prediction (Logistic regression):
Identiﬁed and Dealt with missing data .Modelled data using using one-hot coding for one-hot encoding.
Predict next-day rain by training classification models on the target variable RainTomorrow.
Trained a  logistic regression model.Test the model on train, cross validation and test dataset.
Accuracy: Train data: 85.19%, CV:85.40%, Test data:84.20%.
Compared to a random predictions model. Accuracy: 77%.

