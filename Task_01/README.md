# 🛍️ Retail Sales Data Analysis | Oasis Infobyte Internship

## 📌 Project Overview

This project was completed as part of the **Oasis Infobyte Internship (OIBSIP)**.

The objective of this project is to perform a comprehensive **Exploratory Data Analysis (EDA)** on a retail sales dataset to identify sales trends, customer behaviour patterns, product performance, and actionable business insights.

The analysis focuses on understanding how different factors such as **time, customer demographics, product categories, sales, profit, returns, regions, and customer satisfaction** influence overall retail business performance.

---

## 🎯 Project Objectives

The main objectives of this project are to:

* Perform initial data inspection and data cleaning.
* Identify and handle missing values and duplicate records.
* Calculate descriptive statistics for numerical variables.
* Analyze monthly and quarterly sales trends.
* Explore customer demographics based on age groups and gender.
* Identify the Top 10 best-selling products.
* Analyze revenue and profit across product categories.
* Examine relationships between numerical variables using a correlation heatmap.
* Analyze return rates across product categories.
* Explore regional sales performance.
* Analyze payment methods and order status.
* Compare customer satisfaction across product categories.
* Generate actionable business recommendations based on the findings.

---

## 📊 Dataset Description

The dataset contains retail transaction data with **4,310 records and 21 columns**.

### Key Features

| Column                  | Description                              |
| ----------------------- | ---------------------------------------- |
| `order_id`              | Unique identifier for each order         |
| `order_date`            | Date when the order was placed           |
| `customer_id`           | Unique customer identifier               |
| `customer_name`         | Name of the customer                     |
| `age`                   | Customer age                             |
| `gender`                | Customer gender                          |
| `region`                | Customer/order region                    |
| `city`                  | Customer/order city                      |
| `product_category`      | Category of the product                  |
| `product_name`          | Name of the product                      |
| `quantity`              | Number of units purchased                |
| `unit_price`            | Price per unit                           |
| `discount_pct`          | Discount percentage                      |
| `sales_amount`          | Total sales amount                       |
| `profit`                | Profit generated                         |
| `shipping_cost`         | Cost of shipping                         |
| `payment_method`        | Method used for payment                  |
| `customer_satisfaction` | Customer satisfaction rating             |
| `return_flag`           | Indicates whether the order was returned |
| `order_status`          | Current status of the order              |
| `days_to_ship`          | Number of days required for shipping     |

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## 🧹 Data Cleaning

The following data preparation steps were performed:

* Converted the `order_date` column to datetime format.
* Checked the dataset for missing values.
* Identified and removed duplicate records.
* Removed records with missing essential order information.
* Converted relevant columns to numerical data types.
* Created additional features for analysis, including:

  * Month
  * Quarter
  * Year
  * Customer Age Groups

---

## 📈 Exploratory Data Analysis

The project includes the following analyses:

### 1. Initial Data Inspection

* Dataset shape
* Column names
* Data types
* Missing values
* Duplicate records

### 2. Descriptive Statistics

The following statistics were calculated for numerical variables:

* Mean
* Median
* Mode
* Standard Deviation

### 3. Time Series Analysis

Sales performance was analyzed using:

* 📈 Monthly Sales Trends
* 📈 Quarterly Sales Trends

### 4. Customer Demographics Analysis

Customer behaviour was explored using:

* Customer Age Group Distribution
* Gender Breakdown

### 5. Product Analysis

Product performance was analyzed through:

* 🏆 Top 10 Best-Selling Products
* 📊 Revenue by Product Category
* 💰 Profit by Product Category

### 6. Correlation Analysis

A correlation heatmap was created to explore relationships between numerical variables, including:

* Quantity
* Unit Price
* Discount Percentage
* Sales Amount
* Profit
* Shipping Cost
* Customer Satisfaction
* Days to Ship
## 📊 Key Visualizations

### Monthly Sales Trend
![Monthly Sales Trend](images/monthly_sales.png)

### Top 10 Best-Selling Products
![Top 10 Products](images/top_10_products.png)

### Revenue by Product Category
![Revenue by Category](images/category_revenue.png)

### Correlation Heatmap
![Correlation Heatmap](images/correlation_heatmap.png)

### Return Rate by Product Category
![Return Rate](images/return_rate.png)


### 7. Additional Business Analysis

To generate deeper insights, the following analyses were also performed:

* 🔄 Return Rate by Product Category
* 🌍 Sales by Region
* 💳 Payment Method Analysis
* 📦 Order Status Distribution
* ⭐ Customer Satisfaction by Product Category

---

## 💡 Key Business Insights

The analysis provides insights into several important areas of retail performance:

* Sales performance varies across different months and quarters.
* Product-level analysis helps identify high-demand products.
* Revenue and profit should be analyzed together to understand actual business performance.
* Customer demographics can support better market segmentation.
* Return rates provide insights that may not be visible through sales analysis alone.
* Regional performance can support targeted marketing and inventory decisions.
* Payment preferences provide useful information about customer purchasing behaviour.
* Customer satisfaction and shipping performance are important factors for improving the overall customer experience.

---

## 🚀 Business Recommendations

Based on the exploratory analysis, the following recommendations can help improve business performance:

### 1. Optimize Inventory for High-Demand Products

Maintain sufficient stock levels for top-selling products to reduce the risk of stock-outs and missed sales opportunities.

### 2. Focus on Both Revenue and Profit

Business decisions should not be based on sales revenue alone. Product categories should also be evaluated based on profitability.

### 3. Investigate Product Returns

Categories or products with higher return rates should be investigated to identify possible issues related to product quality, descriptions, customer expectations, or delivery.

### 4. Implement Regional Strategies

Marketing and inventory strategies should be adjusted according to regional sales performance rather than applying the same strategy to every location.

### 5. Improve Customer Experience

Customer satisfaction, shipping time, and order status should be monitored together to identify operational improvements that can improve customer retention.

---

## 📁 Project Structure

OIBSIP/
└── Task1/
    ├── Mehwish_Task1.ipynb
    ├── retail_sales_dataset (1).csv
    ├── README.md
    └── images/
        ├── monthly_sales.png
        ├── top_10_products.png
        ├── category_revenue.png
        ├── correlation_heatmap.png
        └── return_rate.png


## ▶️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/OIBSIP.git
```

### 2. Navigate to the Project Folder

```bash
cd OIBSIP/Task1
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Mehwish_Task1.ipynb
```

and run all cells.

---

## 📌 Project Deliverables

* Complete Exploratory Data Analysis Notebook
* Data Cleaning and Preparation
* Statistical Analysis
* Data Visualizations
* Business Insights
* Actionable Recommendations

---

## 👩‍💻 Author

**Mehwish Iqbal**

Aspiring Data Analyst

## 📬 Contact

🔗 LinkedIn: www.linkedin.com/in/mehwish-iqbal-2584b3395

💻 GitHub: https://github.com/mehwish-Iqbal/data-analyst-portfolio.git

---

## 🏢 Internship

This project was completed as part of the **Oasis Infobyte Internship Program (OIBSIP)**.

---

## ⭐ Conclusion

This project demonstrates the use of **Python and data visualization techniques** to transform raw retail sales data into meaningful business insights.

The analysis provides a structured understanding of **sales trends, customer behaviour, product performance, profitability, returns, and operational factors**. These insights can support better decision-making in areas such as inventory management, marketing strategy, customer segmentation, and business operations.

