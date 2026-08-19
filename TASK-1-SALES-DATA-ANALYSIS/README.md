# Supplement Sales Analysis 📊

This project is part of my internship work, where I explored a supplement sales dataset using Python. The main goal was to understand sales performance, identify popular products and categories, and find some useful patterns in the data.

I used **Pandas, Matplotlib, and Seaborn** for data cleaning, analysis, and visualization.

## About the Project

The dataset contains sales information for different supplement products. It includes details such as:

* Date
* Product Name
* Category
* Units Sold
* Price
* Revenue
* Discount
* Units Returned
* Location
* Platform

There are **4,384 records** and **10 columns** in the dataset.

## What I Did

The project was completed in a few main steps:

1. Loaded the dataset using Pandas.
2. Checked the structure and data types.
3. Checked for missing values and duplicate records.
4. Converted the Date column into a proper datetime format.
5. Used Date as the DataFrame index for time-based analysis.
6. Analyzed monthly revenue trends.
7. Compared sales across different product categories.
8. Identified the top 10 products based on revenue.
9. Compared revenue across different locations.
10. Used a correlation heatmap to understand relationships between numerical variables.

## Visualizations

### Monthly Sales Trend

I grouped the data by month and calculated the total revenue to understand how sales changed over time.

### Sales by Category

This analysis shows which supplement categories generated the highest revenue.

### Top 10 Products

The top 10 products were identified based on their total revenue. This helps understand which products performed best in the dataset.

### Region-wise Sales

Revenue was compared across different locations to see which regions contributed more to overall sales.

### Correlation Heatmap

A correlation heatmap was created for the numerical columns to understand relationships between variables such as units sold, price, revenue, discount, and returned units.

## Tools & Technologies

* **Python**
* **Pandas** – data loading, cleaning and analysis
* **Matplotlib** – data visualization
* **Seaborn** – statistical visualization
* **Google Colab / Jupyter Notebook**
* **GitHub** – project version control

## Project Structure

```text
Supplement-Sales-Analysis/
│
├── Supplement_Sales_Analysis.ipynb
├── README.md
└── dataset/
    └── supplement_sales.csv
```

> The dataset can also be loaded directly from the Google Sheets CSV source used in the notebook.

## Key Learnings

Through this project, I got practical experience with:

* Working with a real-world style sales dataset
* Data cleaning using Pandas
* Handling dates and time-series data
* Grouping and aggregating data
* Finding top-performing products
* Comparing sales across categories and locations
* Creating charts to communicate data findings
* Using GitHub to document and share a project

## Conclusion

This project helped me understand the basic workflow of a data analysis project, starting from loading and cleaning the data and ending with visualizing useful business information.

The analysis can be further improved by adding an interactive **Power BI dashboard**, sales forecasting, customer-level analysis, and more detailed product performance metrics.

## Author

**Vishal Athawale**

Mechanical Engineering Graduate | Aspiring Data Analyst

Skills: **Python | SQL | Excel | Power BI | Data Analysis**

---

⭐ This project was completed as part of my internship learning and practical work in data analysis.
