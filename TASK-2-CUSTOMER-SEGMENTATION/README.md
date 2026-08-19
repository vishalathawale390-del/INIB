# Customer Segmentation using K-Means

## About the Project

This project is part of my Data Analytics internship at Intern InfoByte.

The main idea of this project is to group customers based on their purchasing behavior. I used the Online Retail dataset and applied K-Means clustering to find different types of customers.

Instead of looking at every transaction separately, I created customer-level information such as the number of orders, total quantity purchased, and total amount spent.

## Dataset

The dataset contains online retail transaction information.

Some of the main columns are:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

## Tools Used

- Python
- Pandas
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

## What I Did

The project was completed in the following steps:

1. Loaded and explored the dataset.
2. Checked missing values and duplicate records.
3. Removed transactions with missing Customer IDs.
4. Removed cancelled and invalid transactions.
5. Created a `TotalAmount` column using Quantity × UnitPrice.
6. Grouped the transactions by CustomerID.
7. Created customer-level features based on their purchasing activity.
8. Scaled the features before applying clustering.
9. Used the Elbow Method to find a suitable number of clusters.
10. Applied K-Means clustering.
11. Visualized the customer groups.
12. Compared the different customer segments.

## Customer Features

For the clustering model, I used:

- Total Orders
- Total Quantity
- Total Spent

These features give a basic view of how often customers purchase and how much they buy.

## Elbow Method

The Elbow Method was used to decide the number of clusters for the K-Means model.

![Elbow Method](images/elbow_method.png)

## Customer Segmentation

After selecting the number of clusters, K-Means was applied to the customer data.

![Customer Segmentation](images/customer_segmentation.png)

## Results

The clustering process divided customers into different groups according to their purchasing behavior.

The groups can be compared based on their order frequency, quantity purchased, and total spending. This helps identify customers with different levels of engagement and value.

## Key Takeaway

Customer segmentation can be useful for businesses because not every customer behaves in the same way. Different groups can be targeted with different offers, marketing strategies, and retention activities.

## Project Files

- `Customer_Segmentation.ipynb` - Complete Python analysis
- `images/` - Project visualizations

## Internship

**Intern InfoByte – Data Analytics Internship**

Task 2: Customer Segmentation
