# E-commerce Sales Revenue Analysis

## Project Overview

This project analyzes e-commerce sales transaction data to understand revenue performance, product performance, customer activity, country-level sales, and sales trends over time.

The project follows an end-to-end data analysis workflow using Python, from data cleaning and preparation to KPI analysis, visualization, and business insights.

## Business Questions

* What is the total revenue generated?
* How many orders and units were sold?
* What is the average order value?
* Which products generate the most revenue?
* Which products sell the highest number of units?
* Which countries generate the most revenue?
* How does revenue change over time?
* What business opportunities can be identified from the data?

## Dataset

The dataset contains e-commerce transaction records with the following fields:

* **InvoiceNo** — Invoice or transaction number
* **StockCode** — Product code
* **Description** — Product description
* **Quantity** — Number of units purchased
* **InvoiceDate** — Date and time of transaction
* **UnitPrice** — Price per unit
* **CustomerID** — Customer identifier
* **Country** — Customer's country

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Data Cleaning

The following data-cleaning steps were performed:

* Handled missing values
* Removed exact duplicate records
* Reviewed data types
* Converted date fields into datetime format
* Created a Revenue column from Quantity × UnitPrice
* Prepared the dataset for analysis

## Key KPIs

The analysis focuses on:

* **Total Revenue**
* **Total Orders**
* **Total Units Sold**
* **Total Customers**
* **Average Order Value**

## Analysis Performed

### Product Analysis

Identified the highest-performing products based on revenue and units sold.

### Country Analysis

Compared revenue performance across different countries.

### Time-Series Analysis

Analyzed monthly revenue trends to identify growth patterns and seasonal behavior.

### Customer Analysis

Evaluated customer activity and revenue contribution.

## Visualizations

The project includes visualizations such as:

* Monthly Revenue Trend
* Top 10 Products by Revenue
* Top 10 Products by Quantity Sold
* Revenue by Country
* KPI summaries

## Business Insights

The analysis is used to identify:

* High-performing products
* High-value markets
* Revenue trends
* Potential growth opportunities
* Areas requiring business improvement

## Project Structure

```text
ecommerce-sales-revenue-analysis/
│
├── sales_analysis.ipynb
├── data.csv.zip
├── README.md
└── dashboard/
```

## How to Run the Project

Clone or download the repository and open `sales_analysis.ipynb` in Jupyter Notebook.

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Then run the notebook cells in order.

## Author

**Harsh Jha**

Aspiring Business/Data Analyst
