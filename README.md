 Housing Price Prediction - Linear Regression
 Project Overview
This project aims to predict house prices using Linear Regression based on features such as area, bedrooms, location, and other related attributes.
We use sklearn for modeling, and evaluate the model using MAE, MSE, and R² Score.

Steps Performed
1. Import and Preprocess Dataset
Loaded the dataset Housing.csv.

Handled categorical variables using One-Hot Encoding.

Scaled numerical features using StandardScaler.

Verified there were no missing values.

2. Train-Test Split
Split the dataset into 80% training and 20% testing using train_test_split.

Features (X) and Target (y) were separated (target: price).

3. Model Building - Linear Regression
Trained a Linear Regression model using sklearn.linear_model.LinearRegression.

Fitted the model on training data.

4. Model Evaluation
Evaluated the model's performance using:

Mean Absolute Error (MAE): 0.52

Mean Squared Error (MSE): 0.50

R² Score: 0.65

These metrics suggest the model is acceptable, but there is room for further improvement.

5. Visualization and Interpretation
Plotted Actual vs Predicted house prices using Seaborn.

Extracted and analyzed feature coefficients to understand the impact of each feature.

