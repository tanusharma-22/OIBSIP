Objective:

To predict the quality of wine based on its physicochemical (chemical) properties using supervised machine learning classification models. This project uses Random Forest, Stochastic Gradient Descent, and Support Vector Classifier to analyze how chemical attributes affect wine quality.

🧭 Steps Performed:

1. Data Collection
   
Dataset: WineQT.csv

Contains features like alcohol, density, volatile acidity, etc. with a target variable quality.

2. Data Exploration & Cleaning
   
Checked for missing values and data types.

Performed statistical summaries and plotted distributions.

No major cleaning was needed.

3. Feature Analysis
Explored relationships between chemical properties and quality.

Visualized using heatmaps, boxplots, and pair plots.

4. Data Preprocessing
Separated features (X) and target (y).

Applied train-test split (80-20).

Standardized features for models that require scaling (SGD, SVC).

5. Model Training
Trained three classifiers:

Random Forest

Stochastic Gradient Descent (SGD)

Support Vector Classifier (SVC)

6. Model Evaluation
   
Evaluated models using:

Accuracy

Classification Report (Precision, Recall, F1-score)

Confusion Matrix

7. Visualization
   
Correlation heatmap

Distribution of wine quality

Boxplots (feature vs quality)

Pair plots

Scatter plot (Alcohol vs Volatile Acidity)

🛠️ Tools & Libraries Used:

Python

Pandas (Data manipulation)

NumPy (Numerical operations)

Matplotlib & Seaborn (Data visualization)

Scikit-learn (Machine learning models & evaluation)

✅ Outcome:

Found Alcohol has strong positive correlation with wine quality, while volatile acidity and density show negative correlation.

Best performance observed from Random Forest Classifier.

Classification metrics help evaluate model bias and variance.

