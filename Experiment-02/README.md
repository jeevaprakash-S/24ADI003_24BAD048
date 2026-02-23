SCENARIO 1 — Ocean Water Temperature Prediction (Linear Regression)

Objective: Predict ocean water temperature using environmental and depth-related features.

Dataset (Kaggle – Public): https://www.kaggle.com/datasets/sohier/calcofi

Target Variable:

Water Temperature (T_degC)

Input Features:

Depth (m)

Salinity

Oxygen

Latitude

Longitude

What the notebook does:

Imports required Python libraries such as NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn

Loads the CalCOFI dataset into a Pandas DataFrame

Selects relevant numerical features and the target variable

Handles missing values using mean/median imputation

Performs feature scaling using StandardScaler

Splits the dataset into training and testing sets

Trains a Linear Regression model

Predicts water temperature for test data

Evaluates model performance using:

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

Visualizes:

Actual vs Predicted temperature

Residual error distribution

Improves model performance using:

Feature selection

Regularization techniques (Ridge and Lasso Regression)

SCENARIO 2 — LIC Stock Price Movement Classification (Logistic Regression)

Objective: Classify whether the LIC stock price will increase or decrease based on historical data.

Dataset (Kaggle – Public): https://www.kaggle.com/datasets/debashis74017/lic-stock-price-data

Target Variable (Derived):

Price Movement

1 → Closing price > Opening price

0 → Closing price ≤ Opening price

Input Features:

Open

High

Low

Volume

What the notebook does:

Imports required Python libraries

Loads the LIC stock price dataset into Pandas

Creates a binary target variable (Price Movement)

Handles missing values using forward fill or imputation

Performs feature scaling using StandardScaler

Splits the dataset into training and testing sets

Trains a Logistic Regression model

Predicts stock price movement for test data

Evaluates classification performance using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

Visualizes:

ROC Curve

Feature importance using model coefficients

Optimizes the model using:

Hyperparameter tuning (C, penalty)

Regularization techniques
