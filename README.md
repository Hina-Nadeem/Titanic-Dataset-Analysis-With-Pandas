# Titanic-Dataset-Analysis-With-Pandas


This project explores the Titanic dataset from Kaggle using Python (Pandas, NumPy, and Seaborn). It includes data cleaning, selection, aggregation, sorting, and visualization to derive meaningful insights from the data.

## 🔍 1. Basic Data Exploration
- Loaded the dataset and displayed the first five rows.
- Checked the dataset shape (number of rows and columns).
- Reviewed data types of all columns.
- Identified and counted missing values in each column.

## 🧹 2. Data Cleaning
- Filled missing values in the "age" column with the **median**.
- Dropped the "cabin" column due to a high percentage of missing values.
- Replaced missing values in "embark_town" with the **most frequent value**.

## 🔎 3. Data Selection & Filtering
- Filtered passengers who are **male and over 30 years old**.
- Displayed "name", "age", and "fare" columns for **survivors**.
- Identified passengers who paid **fare > 100**.

## 📊 4. Aggregation & Grouping
- Calculated **average fare per class**.
- Counted number of passengers per **embarkation town**.
- Found **maximum age** for each **gender**.

## 🔢 5. Sorting & Ranking
- Sorted the dataset by **age in descending order**.
- Sorted by **fare (descending)** and then by **age (ascending)**.

## 📈 6. Data Visualization
- Bar chart showing number of **survivors by gender**.
- Histogram of **age distribution**.
- Box plot displaying **fare distribution by passenger class**.

## 📦 Libraries Used
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`

## 🚀 How to Run
1. Clone this repository.
2. Run the Jupyter notebook or Python script in your local environment.
3. Make sure all dependencies are installed.

## 💡 Insights
This project demonstrates fundamental data analysis techniques and helps build skills in data cleaning, transformation, visualization, and interpretation.



