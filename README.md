# Titanic-Survival-Prediction-using-ML

This project focuses on predicting Titanic survival rates using machine learning techniques. It covers the problem statement, workflow steps, data processing, analysis, model training, and evaluation. The logistic regression algorithm is utilized for binary classification.

The dataset used in this project is obtained from Kaggle. It includes details of passengers such as ticket price, gender, age, number of siblings/spouse, number of parents/children, ticket number, fare, cabin number, and embarkation port.

Data Processing and Analysis

- Handling missing values:
  - Dropping the cabin column due to extensive missing data.
  - Replacing missing age values with the mean age.
  - Replacing missing values in the embarked column with the most repeated value (mode).
- Exploring statistical measures and survival patterns through data visualization techniques.

Model Training

- Encoding categorical columns into numerical values.
- Removing specific columns from the dataset.
- Separating the data into training and testing sets using the train_test_split function.
- Training the logistic regression model on the training data.

Model Evaluation

- Evaluating the model's accuracy by comparing predictions with actual values.
- Discussing the concept of overfitting and underfitting.
- Hints at techniques to improve accuracy in machine learning models.

