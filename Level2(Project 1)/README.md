Objective:

To build a predictive model using Linear Regression to estimate house prices based on various numerical features such as area, number of bedrooms, parking space, and more. This project provides hands-on experience in model development, evaluation, and interpretation.

 Steps Performed:
 
1. Data Collection
   
Dataset: Housing.csv

The dataset contains features such as:

area (size of the house)

bedrooms, bathrooms, stories

parking, furnishingstatus

and the target variable: price

2. Data Exploration & Cleaning
   
Explored dataset structure using head(), info(), and describe().

Converted categorical variables (furnishingstatus, mainroad, etc.) using one-hot encoding.

Checked and handled missing values (if any).

3. Feature Selection
   
Identified numerical and relevant categorical variables.

Used domain understanding and correlation matrix to retain useful predictors.

4. Model Training
   
Applied Linear Regression using scikit-learn:

Split data into training and testing sets (80-20 split).

Trained model using LinearRegression().fit(X_train, y_train).

5. Model Evaluation
   
Evaluated model using:

R-squared Score to determine goodness of fit.

Mean Squared Error (MSE) to measure prediction accuracy.

Example Output:

R² Score: ~0.68

MSE: (varies depending on preprocessing and features)

6. Visualization
   
Plotted:

Scatter plot of actual vs predicted prices.

Distribution of residuals.

Correlation heatmap between features.

🛠️ Tools & Libraries Used:

Python

Pandas – data manipulation

NumPy – numerical operations

Matplotlib & Seaborn – visualization

Scikit-learn – machine learning modeling and metrics

✅ Outcome:

Built a baseline Linear Regression model for predicting house prices.

Found features like area, bedrooms, and parking have a strong influence on price.

Identified areas for improvement like feature engineering and outlier treatment.

