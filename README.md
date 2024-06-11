# Mobile-Wallet-Enhancement

## Project Overview
This project involves collaboration between the data science team and the full stack development team at QuickTeller. The goal is to build a model that helps the full stack team better understand user requirements from the mobile wallet app. By leveraging data science techniques, the aim is to enhance user experience and satisfaction with the QuickTeller mobile wallet.

## Dataset
The dataset for this project contains various features that represent user interactions and requirements from the QuickTeller app. Key features might include:

User demographics
Transaction history
Usage frequency
App feedback ratings
In-app behavior metrics
Packages Used
The following Python packages were utilized in this project:

warnings: To manage and ignore warnings.
pandas: For data manipulation and analysis.
matplotlib.pyplot: For plotting and visualizing data.
seaborn: For advanced visualizations.
category_encoders.OneHotEncoder: For encoding categorical features.
sklearn.linear_model.LinearRegression, sklearn.linear_model.Ridge: For implementing linear and ridge regression models.
sklearn.metrics: For evaluating model performance using mean absolute error (MAE) and mean squared error (MSE).
sklearn.impute.SimpleImputer: For handling missing values.
sklearn.pipeline.make_pipeline: For creating a pipeline to streamline data preprocessing and model training.
Model Building
Data Preprocessing
Encoding Categorical Variables: Using OneHotEncoder to convert categorical variables into a numerical format suitable for model training.
Imputation: Handling missing values using SimpleImputer to ensure a complete dataset for model training.
Model Training
Two regression models were trained to predict user requirements:

Linear Regression
Ridge Regression
Evaluation Metrics
The models were evaluated using the following metrics:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Baseline and Performance
Baseline MAE: 1.60
Test MAE: 1.39
Model Coefficients
Intercept: 2.37
Coefficients: [0.31, 1.31, -0.69, -0.69, 0.31]

## Results
The ridge regression model achieved a test MAE of 1.39, outperforming the baseline MAE of 1.60. This indicates that the model is effective in predicting user requirements based on the given features.

## Conclusion
By leveraging linear and ridge regression models, the data science team provided valuable insights into user requirements for the QuickTeller app. This collaboration with the full stack team will help enhance the user experience by better understanding and addressing user needs.

## Future Work
Feature Engineering: Incorporating additional features and refining existing ones to improve model accuracy.
Model Optimization: Experimenting with other regression models and hyperparameter tuning for better performance.
Deployment: Integrating the model into the app to provide real-time user requirement predictions.
