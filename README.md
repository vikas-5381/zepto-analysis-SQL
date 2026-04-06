# 🧾 Zepto Analysis SQL
This SQL project analyzes Zepto product data to uncover insights on pricing, discounts, stock availability, and category performance. It uses data cleaning and exploratory queries to help understand sales trends and optimize inventory and revenue decisions.


## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---

<h2><a class="anchor" id="overview"></a>Overview</h2>

This Zepto SQL project focuses on analyzing product data to gain insights into pricing, discounts, stock status, and category-wise performance. It involves data cleaning, exploration, and advanced queries to identify top products, revenue trends, and best-value items. Overall, it helps in making data-driven decisions for inventory and business growth.

---

<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

- dentify which products and categories generate the highest revenue
- Detect out-of-stock items that may lead to lost sales opportunities
- Analyze the impact of discounts on product sales and profitability
- Find high-priced products with low discounts affecting customer demand
- Optimize inventory by identifying overstocked and understocked products
- Determine best-value products based on price per unit/weight
- Improve pricing and discount strategies to stay competitive
- Support data-driven decision-making for business growth and efficiency

---  

<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- Dataset Size:
Contains multiple product (SKU) records across different categories
Includes fields like MRP, discount, quantity, stock status, and weight
- Time Period:
Represents a static snapshot of product data
No time-series or historical data included
- Data Source:
Derived from Zepto (online grocery delivery platform) dataset
Structured dataset used for SQL-based analysis and learning
- Purpose of Dataset:
To analyze pricing, discounts, and inventory patterns
To support data-driven decisions for revenue and stock optimization

---  

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- SQL (Structured Query Language).
- Database System (PostgreSQL / MySQL).
- Data Processing Technique.
- Basic Analytical Functions.

---  

<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

zepto-analysis/
│
├── README.md
├── .gitignore
├── requirements.txt
├── Zepto Analysis.pdf
│
├── dashboard/                  # SQL File
│   └── zepto_analysis.pbi

---  

<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

- Checked and handled missing/null values in important columns
- Removed invalid records (e.g., products with MRP = 0)
- Converted price values from paise to rupees
- Verified and corrected data types (numeric, boolean, integer)
- Identified duplicate product entries (same name with multiple SKUs)
- Structured data properly for smooth SQL analysis

--- 

<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

- Which products have the highest discounts?
Top products identified with maximum discount percentages
Helps attract price-sensitive customers
- Which high-value products are out of stock?
Found expensive items (high MRP) that are unavailable
Indicates potential revenue loss
- Which categories generate the most revenue?
Certain categories contribute more to total sales
Useful for focusing marketing and inventory efforts
- How do discounts impact product pricing?
Products with higher discounts show better value perception
Helps in optimizing discount strategies
- Which products offer the best value (price per gram)?
Identified cost-efficient products based on weight and price
Helps customers and business compare product value

--- 

<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

- Power BI Dashboard Shows:
- Total Number of Movies and TV Shows
- Content Distribution by Gender
- Release Year Trends
- Country-wise Content Production
- Content Ratings Distribution
- Type of Content Comparison

  --- 

<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Clone the repository:
```bash
git clone https:[//github.com/yourusername/](https://github.com/vikas-5381/prime_vidieo_analysis)
```
3. Load the CSVs and ingest into database:
```bash
prime_vidieo_analysis.xlsx  
```
4. Create sales summary table:
```bash
power bi scripts/get_vidieo_summary.xlsx
```
5. Open Power Bi Dashboard:
 ```bash
   - `Weathher Analysis Dashboard.pbix`
```
---
