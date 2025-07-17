Note: The csv file is too large, that's why i'm not able to upload.

Objective

The objective of this project is to clean a real-world dataset by identifying and addressing:

Missing values

Duplicate records

Inconsistent formatting

Outliers

Clean data is essential for accurate analysis and building reliable machine learning models.

🧾 Dataset Used

Name: CAvideos.csv

Source: Kaggle – YouTube Trending Videos Dataset

Context: This dataset contains metadata for trending YouTube videos in Canada, including views, likes, dislikes, and comments.

🛠️ Tools & Technologies

Tool	Purpose

Python	Main programming language

Pandas	Data manipulation & cleaning

Seaborn	Visualizing outliers

Matplotlib	Supporting visualizations

Jupyter	Notebook-based project workflow

🔧 Steps Performed

Data Loading: Imported the CSV file into a Pandas DataFrame.

Missing Value Handling:

Filled missing values in the description column with "No Description".

Duplicate Removal:

Removed any fully duplicated rows using drop_duplicates().

Standardization:

Standardized string formats where applicable (e.g., lowercase conversions — optional).

Outlier Detection:

Used boxplot to visualize outliers in views.

Removed videos in the top 1% of views using the 99th percentile threshold.

Data Export:

Saved the cleaned dataset to CAvideos_cleaned.csv.

✅ Outcome

Final cleaned dataset: CAvideos_cleaned.csv

Dataset is now ready for EDA, modeling, or dashboarding.

Demonstrated real-world skills in:

Cleaning structured data

Making data analysis-ready

Writing maintainable cleaning code

📌 Project Highlights

Emphasized data integrity and decision-making in missing data treatment.

Illustrated how poor-quality data can be systematically fixed.

Used visual tools to support statistical decisions (like outlier removal).
