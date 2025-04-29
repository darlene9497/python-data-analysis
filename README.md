# 📊 Sales Data Analysis with Python

This project is a basic data analysis using Python and the `pandas` and `matplotlib` libraries. It involves exploring, cleaning, analyzing, and visualizing a sales dataset stored in a CSV file.

## 📁 Dataset

The dataset used is `sales_data.csv`, which contains records of daily product sales with the following columns:

- `Date` (YYYY-MM-DD)
- `Product`
- `Quantity Sold`
- `Revenue ($)`

## ✅ Objectives

- Load and inspect the dataset
- Explore its structure and clean it
- Perform basic statistical analysis
- Generate insights through grouping
- Visualize key trends and patterns using charts

## 📌 Technologies used

- Python 3
- Jupyter Notebook
- pandas
- matplotlib

## 🔍 Key tasks

### 1. Load and explore the dataset
- Loaded the dataset using `pandas.read_csv()`
- Displayed the first few rows with `.head()`
- Inspected data types and missing values

### 2. Data Cleaning
- Checked for null values using `.isnull()`
- Cleaned the data (although no missing values were found)

### 3. Data analysis
- Calculated total revenue
- Identified the best-selling product
- Found the day with the highest revenue
- Grouped data by product to calculate average quantity sold and revenue

### 4. Data visualization
Used `matplotlib` to create:
- 📈 Line chart: Revenue over time
- 📊 Bar chart: Average revenue per product
- 📉 Histogram: Distribution of quantity sold
- ⚫ Scatter plot: Quantity Sold vs. Revenue

## 🚀 How to run

1. Clone the repository or download the files
2. Ensure you have Python and Jupyter Notebook installed
3. Run the notebook or script in your local environment
4. View the visualizations and output
