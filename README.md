# Supply Chain & Logistics Performance Analytics

**An end-to-end data analytics project focused on evaluating e-commerce delivery performance, seller operations, logistics costs, order fulfilment, and customer experience using Python, PostgreSQL, SQL, and Power BI.**

**Project Status:** In Progress

---

## 1. Project Overview

Efficient supply chain and logistics operations are essential for e-commerce businesses. Delivery delays, inconsistent seller performance, increasing freight costs, and poor order fulfilment can negatively affect operational efficiency and customer satisfaction.

This project aims to analyze historical e-commerce order data to evaluate logistics performance, identify operational inefficiencies, investigate delivery-related patterns, and generate actionable business recommendations.

The analysis will use the Olist Brazilian E-Commerce Public Dataset, which contains multiple interconnected datasets covering customers, orders, products, sellers, payments, reviews, and delivery information.

The objective is to transform raw transactional data into meaningful business insights through data cleaning, exploratory data analysis, advanced SQL queries, KPI development, and interactive Power BI dashboards.

## 2. Business Problem

An e-commerce company wants to understand how effectively its order fulfilment and logistics operations are performing.

Management needs answers to questions such as:

- What percentage of orders are delivered late?
- Which sellers experience the highest delivery delays?
- Which product categories have longer delivery times?
- How do actual delivery dates compare with estimated delivery dates?
- How do freight costs vary across products and regions?
- Are delivery delays associated with lower customer review scores?
- What patterns can be identified in cancelled and undelivered orders?
- Which operational areas require improvement?

This project will investigate these questions using historical data and evidence-based analysis.

## 3. Project Objectives

- Analyze overall order fulfilment and delivery performance.
- Measure on-time and late-delivery rates.
- Evaluate seller and product-category performance.
- Investigate regional delivery patterns.
- Analyze freight costs and shipping performance.
- Explore the relationship between delivery outcomes and customer review scores.
- Identify patterns in cancelled and undelivered orders.
- Develop interactive dashboards to communicate findings.
- Provide practical recommendations based on analytical results.

## 4. Dataset

**Dataset:** Olist Brazilian E-Commerce Public Dataset

**Source:** Kaggle

Dataset link: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

The dataset contains nine CSV files:

| Dataset | Description |
|---|---|
| Customers | Customer identifiers and location information |
| Orders | Order status and important order timestamps |
| Order Items | Products, sellers, prices, and freight values |
| Order Payments | Payment methods and payment amounts |
| Order Reviews | Customer review scores and comments |
| Products | Product attributes and categories |
| Sellers | Seller identifiers and location information |
| Geolocation | Geographic coordinates associated with ZIP prefixes |
| Category Translation | Portuguese-to-English product category mapping |

The datasets will be connected using appropriate identifiers and relationships after examining their data grain and key constraints.

## 5. Technology Stack

| Technology | Purpose |
|---|---|
| Python | Data exploration, cleaning, and validation |
| Pandas | Data manipulation and transformation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| PostgreSQL | Relational database management |
| SQL | Business analysis and data querying |
| Power BI | Interactive dashboard development |
| DAX | KPI calculations and analytical measures |
| Power Query | Data transformation |
| Git & GitHub | Version control and project documentation |

## 6. Project Workflow

1. **Business Understanding:** Define business problems, objectives, and analytical questions.
2. **Data Understanding:** Explore all datasets, inspect columns, identify data types, and understand table relationships.
3. **Data Cleaning:** Handle missing values, duplicates, inconsistent records, and date formats using Python.
4. **Database Development:** Import cleaned datasets into PostgreSQL and establish appropriate relationships.
5. **SQL Analysis:** Perform business analysis using joins, aggregations, CTEs, subqueries, and window functions.
6. **Exploratory Data Analysis:** Investigate delivery trends, seller performance, freight costs, and customer reviews.
7. **KPI Development:** Define and calculate operational performance metrics.
8. **Power BI Development:** Build interactive dashboards with DAX measures, filters, and visualizations.
9. **Business Recommendations:** Translate analytical findings into actionable recommendations.
10. **Documentation:** Present the methodology, findings, limitations, and final project outcomes.

## 7. Key Performance Indicators

The following KPIs are planned for the analysis:

- Total Orders
- Delivered Orders
- On-Time Delivery Rate
- Late Delivery Rate
- Average Delivery Time
- Average Delivery Delay
- Cancellation Rate
- Average Freight Cost
- Average Customer Review Score
- Seller Delivery Performance

All KPI definitions and calculation rules will be documented to ensure accurate and consistent reporting.

## 8. Planned Power BI Dashboards

**Dashboard 1: Executive Overview**
- Overall order performance
- Delivery performance KPIs
- Order status distribution
- Freight cost overview

**Dashboard 2: Delivery & Logistics Analysis**
- On-time versus late deliveries
- Actual versus estimated delivery time
- Delivery trends
- Regional delivery performance

**Dashboard 3: Seller & Product Performance**
- Seller performance comparison
- Product-category analysis
- Order volume by seller
- Freight cost analysis

**Dashboard 4: Customer Experience**
- Customer review score distribution
- Delivery performance versus review scores
- Review trends
- Order cancellation patterns

## 9. Repository Structure

```text
Supply-Chain-Logistics-Analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│
├── sql/
│
├── powerbi/
│
├── visuals/
│
├── reports/
│
├── README.md
└── .gitignore
```

**Note:** Raw and processed datasets are excluded from GitHub. Refer to the dataset source above to download the original files.

## 10. Expected Business Outcomes

The project aims to provide data-driven insights that can help an e-commerce business:

- Monitor delivery and order fulfilment performance.
- Identify sellers and regions with weaker delivery outcomes.
- Understand freight-cost variations.
- Investigate delivery-related customer satisfaction patterns.
- Identify operational inefficiencies.
- Make better-informed logistics and operational decisions.

These are intended outcomes, not verified findings. Final recommendations will be based on the actual analysis.

## 11. Project Limitations

- The analysis is based on historical Brazilian e-commerce data.
- The dataset does not contain direct warehouse inventory or stock-on-hand information.
- Delivery patterns observed in this dataset should not automatically be generalized to other markets.
- Relationships between delivery performance and review scores will be treated as associations unless causal evidence is established.

## 12. Author

**Uveshkhan Lohani**

B.E. Information Technology | Aspiring Data Analyst

- GitHub: https://github.com/Uveshkhan2005
- LinkedIn: https://www.linkedin.com/in/uveshkhan-lohani-615793273/

---
