
 Objective
The aim of this project is to explore, clean, and analyze the Google Play Store dataset to gain deep insights into app categories, user behavior, pricing strategies, ratings, and reviews. The project leverages data science and visualization techniques to draw conclusions about the Android app ecosystem.

📦 Datasets Used

File Name	Description

apps.csv	Contains metadata about apps (name, category, rating, installs, etc.)

user_reviews.csv	Contains user reviews and sentiment labels

🔧 Tools & Libraries Used

Tool/Library	Purpose

Python	Programming language

Pandas	Data manipulation and cleaning

NumPy	Numerical calculations

Matplotlib	Static visualizations


Seaborn	Correlation and distribution plots

Plotly	Interactive visualizations

Streamlit 	Interactive app deployment

🧪 Project Steps
1. 📁 Data Preparation
Loaded apps.csv and user_reviews.csv

Cleaned missing and inconsistent values

Converted Size, Installs, and Price columns to numeric types

Filtered and encoded categorical data

2. 🧭 Category Exploration
Counted number of apps in each category

Visualized distribution using bar plots

Analyzed most popular categories by number of installs and total reviews

3. 📊 Metrics Analysis
Ratings: Examined average ratings and rating distribution by category

Size: Investigated size trends among free and paid apps

Price: Analyzed price distribution and identified premium apps

Popularity: Explored installs vs. rating correlation

4. 💬 Sentiment Analysis
Merged review data with app metadata

Analyzed sentiment (Positive, Neutral, Negative) by app and category

Visualized sentiment distribution using count plots and pie charts

5. 📈 Interactive Visualizations
Used plotly.express to create interactive bar charts and scatter plots

Filtered dashboards using dropdowns (with Altair or Streamlit, optional)

📊 Key Visualizations

Bar Chart	Number of apps per category

Heatmap	Correlation between app features

Boxplot	Rating distribution by app type

Scatter	Size vs. Rating, Installs vs. Rating

Pie Chart	Sentiment distribution

Line Chart	Average rating or installs over time (if available)

 Key Insights

Most apps are free, but paid apps tend to be smaller in size and less popular.

Categories like Games, Tools, and Productivity dominate the market.

Sentiment analysis shows most users are positive, but paid apps receive more polarized feedback.

There is a moderate correlation between installs and rating, suggesting downloads may affect perception.

Large-sized apps are generally found in productivity or media categories.

Learning Outcomes

 Developed skills in:

Data cleaning and feature engineering

Exploratory data analysis on real-world data

Sentiment analysis using text data

Visualization with both static and interactive tools

Communicating findings clearly and effectively

