📌 Task 3 – Linear Regression (House Price Prediction)
🔹 Objective

The goal of this task is to implement and understand Linear Regression (both simple and multiple) to predict house prices based on features like Area and Bedrooms.

🔹 Tools Used

Python

Pandas → Data handling

Matplotlib → Data visualization

Scikit-learn → Machine Learning (Linear Regression, train-test split, evaluation metrics)

🔹 Steps Performed

Import & Preprocess Data

Loaded dataset (house_prices.csv) using Pandas.

Checked missing values, duplicates, datatypes.

Selected features (Area, Bedrooms) as independent variables and Price as target.

Train-Test Split

Split data into training (80%) and testing (20%) sets using train_test_split.

Fit Linear Regression Model

Used LinearRegression() from sklearn.

Trained the model on training data.

Evaluate Model

Calculated error metrics:

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

R² Score (Goodness of fit)

Plot Regression Line

Visualized actual vs predicted prices (for Area).

Showed regression line to understand the model fit.

Interpret Coefficients

Coefficients explained the effect of each feature:

Example: If coefficient of Area = 150 → For every 1 sq.ft increase, price increases by ₹150.

Example: If coefficient of Bedrooms = 20000 → Adding one bedroom increases price by ₹20,000.

Intercept represents the base house price when features are zero.

🔹 Results

The model was successfully trained and evaluated.

Performance metrics (MAE, MSE, R²) gave insights into accuracy.

Regression line visualization showed how well the model fits actual data.

Feature coefficients provided interpretability (how much each factor contributes to price).

🔹 Learning Outcome

Understood the concept of Linear Regression (simple & multiple).

Learned how to preprocess data, split dataset, and train a regression model.

Gained experience in evaluating model performance with standard metrics.

Learned to visualize regression line and interpret model coefficients.
