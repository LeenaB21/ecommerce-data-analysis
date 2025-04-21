# E-Commerce Data Analysis Project

This project explores an e-commerce dataset through data cleaning, exploratory analysis, and time series insights using Python. It also includes interactive Power BI dashboards to visualize customer satisfaction, product trends, and delivery performance for business decision-makingIt is organized into three main Jupyter Notebooks:

## Notebooks Overview

### 1. Data Cleaning & Preprocessing (`1_Data_cleaning&Preprocessing.ipynb`)
- Merges data from multiple CSV files.
- Handles missing values and outliers.
- Fixes data types and creates new features (e.g., delivery days).
- Removes duplicates.

### 2. Exploratory Data Analysis (EDA) (`2_EDA.ipynb`)
- Visualizes key trends in the data:
  - Price distribution.
  - Review score distribution.
  - Top 10 product categories by order count.
  - Price vs freight value.
  - Top 10 products by order frequency.
  - Delivery time distribution.

### 3. Time Series Analysis (`3_time_series_analysis.ipynb`)
- Analyzes time-series trends over time:
  - Monthly order trend.
  - Monthly revenue trend.
  - Monthly delivery time trend.

## Power BI Dashboard

An interactive Power BI dashboard was created to present key business insights. It includes:

- Key performance indicators such as total sales, order volume, delivery performance, and customer satisfaction.
- Visualizations for sales by product category, order volume over time, review score distribution, and delivery status breakdown.
- Helps stakeholders identify trends and make data-driven decisions.

![Power BI Dashboard](images/dashboard_screenshot.png)

## Modules Used

The following Python libraries are used in this project:

- pandas: For data manipulation and analysis.
- matplotlib and seaborn: For visualizations (bar plots, line plots, histograms, scatter plots, etc.).
- jupyter: For running and interacting with notebooks.

## Requirements

Install the necessary libraries using the following:

```bash
pip install -r requirements.txt
```

## Folder Structure

```
/notebooks
    1_Data_cleaning&Preprocessing.ipynb
    2.EDA.ipynb
    3.time_series_analysis.ipynb
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/LeenaB21/ecommerce-data-analysis
```

2. Navigate to the `notebooks` folder:

```bash
cd notebooks
```

3. Run the notebooks using Jupyter:

```bash
jupyter notebook
```
