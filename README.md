# Olist E-Commerce Sales \& Performance Analysis

## 📊 Project Overview

An end-to-end **Data Analytics and Business Intelligence project** analyzing the performance of the Brazilian Olist e-commerce marketplace using **Power BI**.

The project transforms raw transactional data into an interactive three-page dashboard covering **sales performance, customer behavior, product categories, payment methods, delivery operations, sellers, and customer satisfaction**.

The objective was not only to visualize the data, but to identify **actionable business insights and recommendations** that could support better commercial and operational decisions.

\---

## 🎯 Business Objectives

The analysis was designed to answer the following business questions:

* How is the marketplace performing overall?
* How are sales and orders evolving over time?
* What is the average order value?
* Which product categories generate the most revenue?
* How strong is customer retention?
* What proportion of customers are returning?
* Which payment methods and installment plans are most popular?
* How well are orders being delivered?
* Which states have the strongest and weakest delivery performance?
* How does delivery time relate to customer satisfaction?
* Where are the main opportunities for business improvement?

\---

## 🛠️ Tools \& Technologies

* **Power BI** — Dashboard development and visualization
* **Power Query** — Data cleaning and transformation
* **DAX** — Business metrics and analytical calculations
* **Excel / CSV** — Data sources and preparation
* **Relational Data Modeling** — Connecting customers, orders, products, sellers, payments, and reviews

\---

## 📁 Dataset

The project uses the **Brazilian Olist E-Commerce Public Dataset**.

The dataset contains multiple interconnected tables covering:

* Orders
* Customers
* Order Items
* Products
* Sellers
* Payments
* Reviews

Key identifiers such as `order_id`, `customer_id`, `product_id`, and `seller_id` were used to connect the different business entities.

\---

## 🧹 Data Preparation

The data was prepared using Power Query before being analyzed in Power BI.

Key preparation steps included:

* Reviewing missing and blank values
* Standardizing data types
* Preparing date and timestamp fields
* Calculating delivery duration
* Classifying orders as on-time or late
* Preparing customer purchase history
* Translating product categories from Portuguese to English
* Preparing payment information for analysis
* Creating analytical fields required for the dashboard

\---

## 🧮 DAX \& Data Modeling

DAX measures were created to transform the transactional data into business KPIs.

Key calculations included:

* Total Sales
* Total Orders
* Average Order Value
* Unique Customers
* Sales Growth
* Repeat Customers
* Repeat Customer Rate
* Orders per Customer
* Average Delivery Time
* On-time Delivery Rate
* Late Delivery Rate
* Average Review Score
* Average Payment Value
* Sales by Category
* Products Sold

The project also demonstrates the use of advanced DAX concepts including:

* `CALCULATE()`
* `TREATAS()`
* `DISTINCTCOUNT()`
* `DIVIDE()`
* Filter context
* Cross-table calculations
* Customer segmentation

\---

# 📈 Dashboard

The final Power BI dashboard consists of three analytical pages.

## 1\. Executive Overview

**Purpose:** Provide a high-level view of marketplace performance.

### KPIs

|KPI|Result|
|-|-:|
|Total Sales|**R$13.59M**|
|Total Orders|**99.44K**|
|Average Order Value|**R$136.68**|
|Unique Customers|**96.10K**|
|Sales Growth|**119.02%**|

### Visuals

* Sales Trend
* Payment Method Distribution
* Monthly Orders Trend

### Business Question

> **How is the marketplace performing overall?**

\---

## 2\. Customers \& Products

**Purpose:** Understand customer behavior and identify the products and categories driving revenue.

### KPIs

* Unique Customers
* Repeat Customers
* Repeat Customer Rate
* Orders per Customer

### Visuals

* New vs. Returning Customers
* Top 10 Products by Sales
* Category Performance
* Products Sold by Year

### Business Question

> **Who is buying, how loyal are customers, and which products and categories drive the business?**

\---

## 3\. Operations \& Performance

**Purpose:** Evaluate delivery operations and customer experience.

### KPIs

|KPI|Result|
|-|-:|
|Average Delivery Time|**12.09 days**|
|On-time Delivery Rate|**91.89%**|
|Late Delivery Rate|**8.11%**|
|Average Review Score|**4.09 / 5**|

### Visuals

* Delivery Performance by State
* Seller Performance
* Review Score vs. Delivery Time
* Payment Installment Distribution

### Business Question

> **How efficiently are orders fulfilled, and how does operational performance relate to customer satisfaction?**

\---

# 🔍 Key Business Insights

## Strong Marketplace Growth

The marketplace generated approximately **R$13.59M in sales across 99.44K orders**.

Sales increased substantially throughout 2017, reaching approximately **R$1.01M in November 2017** from **7,544 orders**.

The November AOV was **R$133.92**, slightly below the overall AOV of R$136.68, indicating that the sales peak was primarily driven by **higher order volume** rather than substantially higher spending per order.

\---

## Customer Retention Is a Major Opportunity

The overall **repeat customer rate was only 3.12%**.

New customers consistently represented the majority of customer activity throughout the analyzed period.

This suggests that marketplace growth was strongly acquisition-driven and that improving customer retention could represent an important opportunity for future growth.

\---

## Revenue Is Concentrated Among Leading Categories

The five largest revenue-generating categories were:

1. **Beauty \& Health**
2. **Watches \& Gifts**
3. **Bed, Bath \& Table**
4. **Sports \& Leisure**
5. **Computers \& Accessories**

Together, these categories generated approximately **R$5.40M**, representing roughly **39.7% of total sales**.

**Beauty \& Health** was the largest category, generating approximately **R$1.26M** with a **4.18 average review score**.

\---

## Revenue and Product Volume Are Not the Same

Bed, Bath \& Table sold **3,029 products**, more than Beauty \& Health's 2,444 products, but generated less revenue.

Watches \& Gifts generated approximately **R$1.21M** from only **1,329 products sold**.

This demonstrates that product volume alone does not determine revenue performance.

\---

## Payment Behavior Is Highly Concentrated

Credit cards represented approximately **73.9% of payment records**, while Boleto represented approximately **19.1%**.

Together, these two payment methods accounted for approximately **93% of recorded payment records**.

Approximately **84% of orders were paid in one to four installments**, demonstrating a strong preference for shorter installment plans.

\---

## Delivery Performance Varies by State

The overall on-time delivery rate was **91.89%**, but significant geographic differences were observed.

* **RO:** 97.11% on-time delivery
* **AL:** 76.13% on-time delivery

AL also had a **23.87% late-delivery rate**, compared with the marketplace-wide rate of 8.11%.

This makes regional logistics performance an important area for further investigation.

\---

## Delivery Time Is Associated With Customer Satisfaction

The analysis identified an overall negative relationship between delivery time and review scores.

Reviews were generally higher for shorter delivery times and progressively lower as delivery duration increased.

For example:

* Around 15 days: average reviews generally above **4.2**
* Around 20 days: approximately **4.0**
* Around 30 days: approximately **3.0**
* Around 40+ days: generally below **2.5**

This indicates that longer delivery times are associated with lower customer satisfaction.

**Note:** This is an observed association and does not prove that delivery time alone causes lower review scores.

\---

# 💡 Business Recommendations

Based on the analysis, the following actions could be considered:

### 1\. Improve Customer Retention

Investigate:

* Personalized recommendations
* Loyalty programs
* Targeted offers
* Post-purchase engagement
* Customer reactivation campaigns

### 2\. Investigate Regional Delivery Problems

Prioritize states with high late-delivery rates and investigate potential causes such as:

* Carrier performance
* Transportation infrastructure
* Seller location
* Distance
* Regional fulfillment capacity

### 3\. Reduce Excessively Long Delivery Times

Monitor both:

**On-time delivery** — whether the order met the promised date

and

**Delivery speed** — how long the customer actually waited.

### 4\. Investigate Seller Performance

Identify sellers with:

* High late-delivery rates
* Long delivery times
* Low customer review scores

### 5\. Focus on High-Performing Categories

Continue supporting major revenue-generating categories while monitoring:

**Revenue + Sales Volume + Customer Satisfaction**

rather than relying on sales alone.

\---

# ⚠️ Data Limitations

Several limitations should be considered when interpreting the findings.

* Some periods at the beginning and end of the dataset are incomplete.
* Product IDs are anonymous, limiting detailed product-level analysis.
* Payment records are not necessarily equivalent to unique orders because an order can contain multiple payment records.
* Categories with very few observations can produce unstable average review scores.
* The relationship between delivery time and review scores represents an association, not proof of causation.
* The dataset represents historical Olist marketplace activity and may not reflect current market conditions.

\---

# 📌 Key Takeaways

The project identifies two particularly important opportunities:

### Customer Retention

**3.12% repeat customer rate**

Olist successfully acquired customers, but relatively few returned to make additional purchases.

### Logistics \& Customer Experience

**8.11% late-delivery rate**

and a clear negative association between longer delivery times and review scores indicate that improving the delivery experience could potentially strengthen customer satisfaction.

\---

# 📂 Repository Structure

```text
Olist-Ecommerce-Analysis/

│

├── README.md

│

├── Documentation/

│   ├── Business_Insights.docx

│   └── Project_Documentation.docx

│

├── PowerBI/

│   └── Olist_Ecommerce_Analysis.pbix

│

└── Screenshots/

\&#x20;   ├── Executive_Overview.png

\&#x20;   ├── Customers_Products.png

\&#x20;   └── Operations_Performance.png

```

\---

# 🚀 Project Workflow

```text
Raw Olist Data
       ↓
Data Cleaning & Preparation
       ↓
Data Modeling
       ↓
DAX Measures
       ↓
Exploratory Analysis
       ↓
Power BI Dashboard
       ↓
Business Insights
       ↓
Business Recommendations
```

\---

# 👤 Author

**Younes Ait El jide**

Data Analyst | Data Science

This project demonstrates practical skills in **data cleaning, data modeling, SQL/DAX-style analytical thinking, Power BI visualization, business analysis, and insight generation**.

\---

## 📄 Detailed Documentation

For the complete methodology, data preparation process, data model, DAX calculations, dashboard design, business insights, recommendations, and limitations, see:

**`PROJECT_DOCUMENTATION.docx`**

