# Diabetes-Prediction-Using-Machine-learning
The goal of this research is to utilize machine learning techniques to estimate the likelihood of diabetes using the "diabetes_012_health_indicators_BRFSS2015.csv" dataset.  Age, BMI, smoking status, physical activity, and other health-related characteristics that are frequently connected to diabetes risk are included in the dataset.
This code uses the "diabetes_012_health_indicators_BRFSS2015.csv" dataset to create a machine learning pipeline that predicts the risk of diabetes.
 The process consists of:

- Data preprocessing (using Isolation Forest to find outliers, scaling, and handling missing values).

- dividing the dataset into sets for testing and training also using SMOTE, Startified sampaling,

- utilizing several models (XGBoost, Random Forest, Neural Network, and Logistic Regression).

- adjusting hyperparameters using RandomizedSearchCV.

 -assessing models using metrics like the Confusion Matrix, Accuracy, and F1-score.

 -evaluating model performance in order to determine the best method for diabetes prediction.
