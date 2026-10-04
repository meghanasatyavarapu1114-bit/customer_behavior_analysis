#Customer Shopping Behavior Analysis

## Overview

This project analyzes **customer shopping behavior** using Python, SQL, and Power BI to identify purchasing patterns, customer segments, sales trends, and business insights.

The project follows an end-to-end **Data Analytics workflow**, starting from data loading and cleaning to SQL analysis, dashboard creation, reporting, and presentation.

## Objectives

- Understand customer purchasing behavior
- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess the dataset
- Analyze business questions using SQL
- Create an interactive Power BI dashboard
- Identify important sales and customer trends
- Present findings through a report and presentation

## Dataset

The dataset contains customer shopping information such as:

- Customer demographics
- Age and gender
- Product categories
- Purchase amount
- Shopping frequency
- Discounts and subscriptions
- Payment methods
- Previous purchases
- Customer ratings

The dataset was loaded into Python for initial exploration, cleaning, and analysis.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| **Python** | Data loading, cleaning & EDA |
| **Pandas** | Data manipulation |
| **NumPy** | Numerical analysis |
| **Matplotlib / Seaborn** | Data visualization |
| **SQL** | Business data analysis |
| **PostgreSQL / MySQL / SQL Server** | Database querying |
| **Power BI** | Interactive dashboard |
| **Gamma** | Presentation creation |
| **Jupyter Notebook** | Python analysis |
| **GitHub** | Project documentation & version control |

## Project Workflow

### 1. Load Dataset

The dataset was imported into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("shopping_behavior.csv")

df.head()
```

### 2. Exploratory Data Analysis

EDA was performed to understand the structure and characteristics of the data.

Key activities included:

- Checking dataset shape
- Inspecting data types
- Statistical analysis
- Identifying missing values
- Checking duplicate records
- Understanding categorical variables
- Analyzing distributions and trends

Example:

```python
df.info()
df.describe()
df.isnull().sum()
```

### 3. Data Cleaning

The dataset was cleaned before further analysis.

Major steps included:

- Handling missing values
- Removing duplicate records
- Correcting data types
- Standardizing categorical values
- Creating required calculated columns
- Validating the cleaned dataset

### 4. SQL Analysis

The cleaned dataset was imported into a relational database.

SQL queries were used to answer important business questions such as:

- What is the total revenue?
- Which product categories generate the highest sales?
- Which age groups contribute the most revenue?
- What are the most popular products?
- Which customers have higher purchase frequency?
- How do different customer segments perform?
- What is the impact of discounts on purchasing behavior?

SQL was implemented using databases such as:

- PostgreSQL
- MySQL
- SQL Server

### 5. Power BI Dashboard

The analyzed data was connected to Power BI to create an interactive dashboard.

The dashboard includes key KPIs and visualizations such as:

- Total Revenue
- Total Customers
- Average Purchase Amount
- Customer Segments
- Revenue by Age Group
- Revenue by Category
- Sales by Gender
- Purchase Frequency
- Subscription Analysis
- Payment Method Analysis

## Dashboard

The Power BI dashboard provides an interactive view of customer shopping behavior and allows users to explore different customer segments and business metrics.

**Key dashboard features:**

- KPI cards
- Bar charts
- Pie/Donut charts
- Column charts
- Slicers and filters
- Category-wise analysis
- Customer demographic analysis
- Revenue analysis

> Add your Power BI dashboard screenshot here.

```text
![Power BI Dashboard](images/dashboard.png)
```

## Key Results & Insights

The analysis helped identify important patterns in customer purchasing behavior.

### Customer Insights

- Identified important customer segments based on purchasing behavior.
- Analyzed customer preferences across different product categories.
- Compared purchasing patterns across age groups and genders.

### Sales Insights

- Identified high-performing product categories.
- Analyzed revenue contribution across customer segments.
- Identified products and categories with stronger purchasing activity.

### Business Insights

- Analyzed the relationship between discounts and purchases.
- Studied subscription and customer purchasing patterns.
- Identified trends that can support better marketing and customer-retention strategies.

## Project Report

A detailed project report was prepared covering:

1. Introduction
2. Dataset Description
3. Data Cleaning
4. Exploratory Data Analysis
5. SQL Analysis
6. Power BI Dashboard
7. Key Findings
8. Business Recommendations
9. Conclusion

## Presentation

A project presentation was created using **Gamma** to communicate:

- Problem Statement
- Project Objectives
- Dataset
- Methodology
- Data Analysis
- SQL Insights
- Power BI Dashboard
- Key Findings
- Business Recommendations
- Conclusion

## How to Run

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/customer-shopping-behavior-analysis.git
```

### Step 2: Navigate to the Project Folder

```bash
cd customer-shopping-behavior-analysis
```

### Step 3: Install Required Python Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Open Jupyter Notebook

```bash
jupyter notebook
```

Open the project notebook and run the cells sequentially.

### Step 5: Database Analysis

Import the cleaned dataset into **PostgreSQL, MySQL, or SQL Server** and execute the SQL queries provided in the SQL folder.

### Step 6: Power BI

Open the Power BI `.pbix` file and refresh the data connection if required.

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── dataset/
│   └── shopping_behavior.csv
│
├── python/
│   └── customer_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── customer_shopping_dashboard.pbix
│
├── report/
│   └── project_report.pdf
│
├── presentation/
│   └── project_presentation.pdf
│
├── images/
│   └── dashboard.png
│
└── README.md
```

## Business Recommendations

Based on the analysis, businesses can:

- Target high-value customer segments with personalized offers.
- Focus marketing efforts on high-performing product categories.
- Use customer purchase behavior for targeted campaigns.
- Improve customer retention through subscription programs.
- Optimize discount strategies based on customer response.

## Conclusion

This project demonstrates an end-to-end **Data Analytics workflow** using Python, SQL, and Power BI.

It showcases practical skills in:

**Data Cleaning → EDA → SQL Analysis → Data Visualization → Dashboard Development → Business Insights**

The project demonstrates how raw customer data can be transformed into meaningful insights that support **data-driven business decisions**.

## Skills Demonstrated

`Python` `Pandas` `NumPy` `EDA` `Data Cleaning` `SQL` `PostgreSQL` `MySQL` `SQL Server` `Power BI` `Data Visualization` `Business Analysis` `Dashboard Development` `Data Storytelling`

## Author

**Meghana Satyavarapu**

B.Tech – Data Science

📌 Interested in **Data Analytics, Data Science, SQL, Python & Business Intelligence**
