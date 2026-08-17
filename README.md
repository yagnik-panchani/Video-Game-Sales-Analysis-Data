# 🎮 Video Game Sales Analysis

## 📌 Project Overview

This project performs an end-to-end exploratory data analysis (EDA) on a video game sales dataset.

The goal of this project is to analyze historical video game sales across different platforms, genres, publishers, and regions and extract meaningful insights from the data.

This project was built as a hands-on learning project to strengthen my practical skills in Python data analysis and data visualization.

---

## 🎯 Objectives

The main objectives of this project are:

- Understand and inspect the dataset
- Handle missing values and duplicate records
- Perform data validation and cleaning
- Analyze descriptive statistics
- Identify the best-selling games
- Analyze sales by genre, platform, publisher, and year
- Compare sales across different regions
- Analyze correlations between regional and global sales
- Perform time-based analysis
- Practice advanced Pandas operations such as GroupBy and Pivot Tables
- Perform basic feature engineering
- Generate meaningful business insights

---

## 📊 Dataset

The dataset contains historical video game sales information.

### Main Features

| Column | Description |
|---|---|
| Name | Name of the video game |
| Platform | Platform on which the game was released |
| Year | Release year |
| Genre | Game genre |
| Publisher | Game publisher |
| NA_Sales | Sales in North America |
| EU_Sales | Sales in Europe |
| JP_Sales | Sales in Japan |
| Other_Sales | Sales in other regions |
| Global_Sales | Global sales |

Sales values are represented in millions of units.

---

## 🧹 Data Cleaning

The following data-cleaning techniques were performed:

- Checked dataset shape and structure
- Identified missing values
- Handled missing Year values
- Converted Year into an appropriate data type
- Checked for duplicate records
- Checked for negative sales values
- Validated Global Sales against regional sales
- Created a clean dataset for analysis

---

## 📈 Exploratory Data Analysis

The project analyzes:

### Game Performance

- Top 10 best-selling games
- Lowest-selling games
- Average and median global sales
- Sales distribution
- Outlier detection using the IQR method

### Genre Analysis

- Number of games by genre
- Total sales by genre
- Average sales by genre
- Regional genre performance

### Platform Analysis

- Number of games released per platform
- Total sales by platform
- Average sales per game
- Platform performance across different years

### Publisher Analysis

- Publishers with the most games
- Publishers with the highest total sales
- Publisher performance across different regions

### Regional Analysis

Sales were compared across:

- North America
- Europe
- Japan
- Other regions

### Time-Based Analysis

- Games released per year
- Global sales by year
- Average sales per game by year
- Top genre by year
- Top platform by year

---

## 📊 Visualizations

The project uses Matplotlib and Seaborn to create visualizations such as:

- Histograms
- Bar charts
- Count plots
- Box plots
- Scatter plots
- Correlation heatmaps
- Time-series plots

---

## 🔧 Advanced Pandas Operations

The project also includes practical usage of:

- `groupby()`
- `agg()`
- `sort_values()`
- `pivot_table()`
- `idxmax()`
- `idxmin()`
- `quantile()`
- Boolean filtering
- Feature engineering
- Statistical analysis

---

## ⚙️ Feature Engineering

Additional features were created to analyze regional contribution and game performance.

Examples include:

- North America sales percentage
- Europe sales percentage
- Japan sales percentage
- Other region sales percentage
- Game sales categories

Games were categorized as:

- **Blockbuster:** > 10 million
- **Hit:** 1–10 million
- **Average:** 0.1–1 million
- **Low:** < 0.1 million

---

## 💡 Key Questions Explored

Some of the major questions explored in this project include:

1. Which games have the highest global sales?
2. Which genre generates the highest total sales?
3. Which platform has the highest total sales?
4. Which publishers have the highest sales?
5. Which region contributes the most sales?
6. How have video game sales changed over time?
7. Which genres are popular in different regions?
8. Which platforms dominated different years?
9. Which publishers perform best in different regions?
10. What characteristics are associated with high-selling games?

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---


