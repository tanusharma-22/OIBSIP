Objective

The primary goal of this project is to perform customer segmentation for an e-commerce company. By analyzing customer behavior, purchase history, and demographics, the aim is to group customers into meaningful clusters. These segments can help businesses design targeted marketing strategies, improve customer satisfaction, and optimize overall performance.

📂 Dataset

Name: ifood_df.csv

Description: The dataset contains customer demographic information, income, product spending details, and purchase behaviors across various channels.

🧰 Tools & Libraries Used

Language: Python

IDE: Jupyter Notebook

Libraries:

pandas – Data manipulation

numpy – Numerical computation

matplotlib, seaborn – Data visualization

sklearn – Preprocessing and clustering (KMeans, StandardScaler)

🔍 Steps Performed

1. Data Collection

Loaded the dataset (ifood_df.csv) into a pandas DataFrame.

2. Data Exploration & Cleaning

Inspected the structure and distribution of data.

Checked for missing values and handled them (e.g., dropping rows with NaNs in Income).

Removed or capped outliers where necessary.

Selected relevant features for clustering:

Income

Recency

Spending on Wines, Fruits, Meat, Fish, Sweets, Gold

Number of purchases via Web, Store, Catalog

Number of deals purchased

3. Descriptive Statistics

Calculated key metrics like:

Average income

Average purchase per product category

Frequency of purchases via different channels

4. Customer Segmentation

Standardized the selected features using StandardScaler.

Applied KMeans Clustering.

Used the Elbow Method to determine optimal number of clusters (k=4).

Assigned cluster labels to customers.

5. Visualization

Used seaborn and matplotlib to visualize:

Spending patterns across clusters

Customer distribution by income and recency

Cluster size comparison via bar plots

6. Insights & Recommendations

Cluster 0: High-income, high spenders across most categories → target for premium loyalty programs.

Cluster 1: Low spenders but frequent buyers → potential for cross-selling and product bundling.

Cluster 2: Customers with low recency and low purchase → consider re-engagement campaigns.

Cluster 3: Moderate income and selective product interest → personalize recommendations.

📈 Outcome

Successfully segmented the customer base into 4 distinct clusters.

Gained actionable insights into spending behavior and channel preferences.

Ready to support targeted marketing strategies and personalized customer engagement.

✅ Learning Outcomes

Applied real-world clustering (KMeans) on customer data.

Practiced data preprocessing, handling missing values, and scaling.

Developed meaningful visualizations to interpret clusters.

Gained analytical skills to derive business value from raw data.





