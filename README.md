## Krishna Store Sales – Retail Data Analysis Project
### Project Overview
This project analyzes Krishna Store’s online fashion retail sales to understand revenue performance, customer demographics, product category trends, and channel‑wise behavior using transactional order data. The goal is to practice end‑to‑end data analysis similar to my Zepto Product & Inventory Analysis and Domino’s Pizza SQL projects, but focused on apparel/e‑commerce sales.
​

The dataset contains detailed order‑level information such as customer demographics, order status, channel, product category, size, location, and sales amount. Using data cleaning, aggregation, and visualization, I generated insights about revenue, order volume, gender and age‑group behavior, city/state performance, and sales by online platforms.

### Objectives
Import, clean, and structure raw Excel data for analysis in Excel / SQL / Power BI.
​

Explore customer orders by gender, age group, state, city, and sales channel.
​

Identify trends in high‑revenue categories (kurta, set, saree, top, western dress, etc.).
​

Analyze order status (delivered, cancelled, refunded, returned) to understand fulfillment quality.
​

Build aggregated views such as “Sales vs Orders”, “Men vs Women”, “States”, “Order Status”, and “Channels”.
​

Document insights and build a retail analytics case study for my portfolio.

### Dataset Information
Domain: E‑commerce / Fashion Retail (Krishna ethnic wear & apparel).

Format: Excel workbook (.xlsx) with multiple sheets and a detailed transaction table.
​

### Core Sheets / Tables
Krishna Store – Main transaction table with one row per line item.
​

Order ID, Cust ID, Gender, Age, Age Group.

Date, Month.

Status (Delivered, Cancelled, Refunded, Returned).

Channel (Amazon, Myntra, Flipkart, Ajio, Meesho, Nalli, Others).
​

SKU, Category (kurta, set, saree, top, blouse, western dress, etc.), Size, Qty, Currency, Amount.
​

Shipping city, state, postal code, country, B2B flag.
​

Sales vs Orders – Monthly summary of total sales amount and order count (Jan–Dec).
​

Men vs Women – Gender‑wise total sales and share of revenue.
​

Order Status – Counts of orders by status (Delivered, Cancelled, Refunded, Returned).
​

States – State‑wise sales (e.g., Maharashtra, Karnataka, Uttar Pradesh, Telangana, Tamil Nadu, etc.).
​

Age n Gender – Age‑group distribution (Teenager, Adult, Senior) by gender using proportions.
​

Channels – Share of orders by channel (Amazon, Myntra, Flipkart, Meesho, Ajio, Nalli, Others).
​

### Skills and Tools Used
Excel / Google Sheets for cleaning, pivot tables, and summary tables (Sales vs Orders, Men vs Women, States, Channels).
​

Power BI / Tableau (optional extension) for interactive dashboards (time series, maps, bar charts, donut charts).

SQL / MySQL (if loaded into a database) for querying large transaction data.

### Data Analysis Techniques:

Aggregation, filtering, grouping, sorting.

Creating calculated fields (e.g., Age Group, B2B vs B2C split).

KPI calculation (total revenue, number of orders, average order value).

Percentage share and contribution analysis (gender, channel, state, category).

### Key Analytical Concepts Applied
Descriptive statistics: SUM of Amount, COUNT of Order ID, averages, and percentages via pivot tables.
​

#### Segmentation:

Gender‑wise and age‑group‑wise analysis (Teenager, Adult, Senior, Men vs Women).
​

Geography (state‑wise and city‑wise performance).
​

Channel‑wise performance (Amazon, Myntra, Flipkart, Meesho, etc.).
​

Order life‑cycle analysis: Delivered vs Cancelled vs Refunded vs Returned counts.
​

Category and size analysis: Revenue by category (kurta, set, saree, top, etc.) and popular sizes (S–6XL, Free).
​

Time‑series view: Month‑wise sales and orders using the “Sales vs Orders” sheet.
​

### Example Business Questions Solved
What is the total revenue and total number of orders in the given period?

How does sales vs orders vary by month (Jan–Dec)?
​

What is the revenue contribution and order share of Men vs Women customers?
​

Which age group (Teenager, Adult, Senior) contributes most to orders within each gender?
​

Which states drive the highest revenue (e.g., Maharashtra, Karnataka, Uttar Pradesh, Telangana, Tamil Nadu)?
​

What is the split of orders across online channels (Amazon, Myntra, Flipkart, Ajio, Meesho, Nalli, Others)?
​

What is the distribution of order status – how many are delivered vs cancelled, refunded, or returned?
​

Which product categories and sizes are most popular and generate the highest sales?

How does B2B vs B2C sales contribution look if the B2B flag is analyzed?
​

### Learning Outcomes
Stronger understanding of retail sales analytics using a real‑world style transactional dataset.
​

Ability to transform raw line‑item data into clean, structured tables and pivot‑based dashboards.

Practice in segmenting customers by demographics, channel, and geography to derive business insights.

Experience calculating and interpreting KPIs such as total sales, order volume, AOV, and category/channel contribution.

A complete case study project that parallels my Zepto inventory and Domino’s SQL projects, but in the apparel e‑commerce domain.

### Future Improvements
Load the Krishna Store data into MySQL and rewrite the Excel pivot logic as SQL queries for scalability.

Build a full Power BI / Tableau dashboard (monthly trends, state map, gender/age donut, order‑status bar, channel share).

Add customer‑level features (RFM scores, repeat vs new customers) if more data is available.

Model return/cancellation drivers by analyzing relationships with category, channel, state, and age group.

Use Python (Pandas + Matplotlib/Seaborn) for advanced analysis, automation, and report generation.
