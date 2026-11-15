# Online Retail Sales Analysis Using Pandas

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on an Online Retail dataset using **Python and Pandas**. The dataset contains more than **1 million retail transaction records**, including invoice information, products, quantities, prices, customer details, dates, and countries.

The main objective of this project is to clean, transform, analyze, and extract meaningful business insights from the retail transaction data using Pandas.

## 🎯 Project Objectives

- Understand the structure and characteristics of the retail dataset.
- Identify and handle missing values and duplicate records.
- Detect cancelled transactions and invalid quantities or prices.
- Convert and analyze transaction dates.
- Create new analytical features such as total sales, year, month, day, hour, and price categories.
- Analyze overall sales performance.
- Identify top-performing products.
- Analyze customer purchasing behavior.
- Compare sales performance across different countries.
- Analyze sales trends over time.
- Generate meaningful business insights from the data.

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Jupyter Notebook**
- **Matplotlib / Seaborn** for visualization

## 🔍 Project Workflow

### 1. Data Loading and Understanding
- Load the CSV dataset using Pandas.
- Inspect rows and columns.
- Check data types.
- Analyze dataset size.
- Identify missing values and duplicate records.

### 2. Data Quality Analysis
- Analyze missing values.
- Identify duplicate transactions.
- Check negative and zero quantities.
- Check zero and negative prices.
- Identify cancelled invoices.
- Analyze missing customer IDs.
- Validate transaction dates.

### 3. Data Cleaning
- Remove duplicate records.
- Handle missing product descriptions.
- Convert invoice dates into datetime format.
- Remove invalid dates.
- Handle invalid prices.
- Separate cancelled/returned transactions from normal sales.
- Create a cleaned sales dataset for further analysis.

### 4. Feature Engineering
New columns are created to make the analysis easier, including:

- `TotalSales`
- `Year`
- `Month`
- `MonthName`
- `Day`
- `DayOfWeek`
- `Hour`
- `YearMonth`
- `PriceCategory`

The `TotalSales` column is calculated using:

`TotalSales = Quantity × Price`

### 5. Sales Analysis
The project analyzes:
- Total revenue
- Total quantity sold
- Number of invoices/orders
- Average order value
- Monthly sales
- Yearly sales
- Daily sales
- Sales by day of week
- Sales by hour

### 6. Product Analysis
Product-level analysis is performed to identify:
- Best-selling products
- Products generating the highest revenue
- Products with the highest quantities sold
- Product price patterns
- Number of unique products

### 7. Customer Analysis
Customer purchasing behavior is analyzed using:
- Number of customers
- Orders per customer
- Revenue per customer
- Average customer spending
- Top customers by revenue

### 8. Country Analysis
Sales performance is compared across countries based on:
- Revenue
- Quantity sold
- Number of orders
- Number of customers
- Average sales

### 9. Time-Based Analysis
The project examines sales trends across:
- Years
- Months
- Days
- Weekdays
- Hours

This helps identify seasonal patterns and periods of high and low sales activity.

## 📊 Key Pandas Concepts Practiced

This project provides practical experience with:

- `read_csv()`
- `head()`
- `info()`
- `shape`
- `dtypes`
- `isnull()`
- `dropna()`
- `drop_duplicates()`
- `astype()`
- `pd.to_datetime()`
- String operations
- Boolean filtering
- `groupby()`
- `agg()`
- `sum()`
- `mean()`
- `count()`
- `nunique()`
- `sort_values()`
- `pivot_table()`
- Date/time operations using `.dt`
- Feature engineering
- Data aggregation and analysis

## 💡 Business Value

The analysis can help a retail business understand its sales performance, identify high-performing products and customers, recognize important sales periods, and compare performance across different markets.

The project demonstrates how **Pandas can be used to transform a large raw transactional dataset into meaningful business insights**.

## 🏁 Conclusion

This project demonstrates an end-to-end **Pandas-based Exploratory Data Analysis workflow**, starting from raw retail transaction data and progressing through data quality analysis, cleaning, feature engineering, and business analysis.

It provides practical experience in handling a large dataset and applying essential Pandas techniques that are commonly used in **Data Analyst and Business Analyst roles**.
