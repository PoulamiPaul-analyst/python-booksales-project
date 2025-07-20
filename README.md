# python-booksales-project
# 📊 Book Sales Data Analysis

This project analyzes a dataset of book sales to explore trends in publishing, author performance, sales metrics, genres, languages, and more — using Python, Pandas, Matplotlib, and Seaborn.

## 📂 Dataset Overview

The dataset includes columns like:

- `Book Name`
- `Author`
- `Genre`
- `Language Code`
- `Publishing Year`
- `Gross Sales`
- `Publisher Revenue`
- `Units Sold`
- `Book Ratings Count`
- `Book Average Rating`
- `Author Rating`
- `Publisher`
- `Sale Price`

## 🧰 Technologies Used

- **Python** (Pandas, NumPy)
- **Matplotlib** & **Seaborn** (for visualizations)
- **Jupyter Notebook** (for analysis)

## 📈 Key Analyses Performed

- Language-wise and genre-wise book distribution (pie, bar, and line charts)
- Box plots for:
  - `Units Sold` by `Author Rating`
  - `Book Ratings Count` by `Genre`
- Time series line plot of `Units Sold` by `Publishing Year`
- Author-wise and publisher-wise total revenue & gross sales (bar charts)
- Relationship between `Book Average Rating` and `Book Ratings Count` (scatter plot)
- Data cleaning: handling missing/null values, removing non-ASCII characters

## 📊 Sample Visualizations

- Bar chart: **Top 5 Authors by Gross Sales**
- Pie chart: **Language Distribution**
- Line chart: **Units Sold by Publishing Year**
- Box plot: **Book Ratings Count by Genre**

📦book-sales-analysis
 ┣ 📊 notebooks/
 ┃ ┗ book_sales_analysis.ipynb
 ┣ 📁 data/
 ┃ ┗ book_sales_data.csv
 ┣ 📄 README.md
