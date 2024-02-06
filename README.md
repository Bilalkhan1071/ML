# Premier League Match Predictor
This Python script aims to predict the outcomes of Premier League matches using historical data. It utilizes machine learning techniques, particularly a Random Forest Classifier, to make predictions based on various match statistics.

# How It Works
Data Preparation: The script reads in match data from a CSV file and performs preprocessing tasks such as handling missing values, converting data types, and creating additional features.

Model Training: After preparing the data, it trains a Random Forest Classifier using a subset of the data as training data. The classifier is trained to predict match outcomes (Win/Loss) based on features such as expected goals (xG), expected goals against (xGA), venue, opponent, hour, and day of the week.

Model Evaluation: Once trained, the model is evaluated using a separate subset of the data as test data. Evaluation metrics such as accuracy and precision are calculated to assess the model's performance.

Prediction: Finally, the trained model is used to predict the outcomes of future matches. The predictions are made based on the rolling averages of certain match statistics to account for recent team performance.

# Requirements
Python 3.x
pandas
scikit-learn
