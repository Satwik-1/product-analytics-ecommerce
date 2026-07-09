# product-analytics-ecommerce
End-to-end product analytics project using SQL and Python to analyze user behavior, conversion funnels, retention, behavioral segmentation, and experimentation strategy for an e-commerce platform.
# End-to-End Product Analytics for an E-Commerce Platform

A product analytics case study using **SQL** and **Python** to analyze customer behavior, conversion funnels, retention, behavioral segmentation, and experimentation strategy to generate actionable business recommendations.

---

## Project Overview

Understanding how users interact with a product is essential for improving customer experience and driving long-term business growth. In this project, I analyzed over **2.7 million customer events** from a real e-commerce platform to identify opportunities for improving user engagement, conversion, and retention.

Using **SQL** and **Python**, I explored the complete customer journey—from browsing products to completing purchases—through funnel analysis, cohort retention, behavioral segmentation, KPI reporting, and product analytics frameworks. The project concludes with data-driven business recommendations and an experimentation roadmap demonstrating how these insights could be validated through A/B testing.

---

## Business Problem

An e-commerce platform wants to better understand customer behavior in order to improve long-term product growth.

This project answers questions such as:

- Where do users drop off in the purchasing journey?
- Which customer behaviors lead to purchases?
- How well does the platform retain users over time?
- Which product metrics should leadership prioritize?
- What experiments should be run to improve business performance?

---

## Dataset

This project uses the publicly available **RetailRocket E-Commerce Dataset**, which contains anonymized user interactions collected from a real online retail platform.

The analysis uses four datasets:

- **events.csv** – Customer interactions (views, cart additions, purchases)
- **item_properties_part1.csv** – Historical product attributes
- **item_properties_part2.csv** – Additional historical product attributes
- **category_tree.csv** – Product category hierarchy

**Dataset:** https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset

After downloading, place the four CSV files inside the `data/` directory before running the notebook.

---

# Project Workflow

This project follows a complete product analytics workflow:

1. Data Preparation
2. Exploratory Data Analysis
3. SQL-Based Product Analytics
4. Funnel Analysis
5. Category Performance Analysis
6. Customer Retention & Cohort Analysis
7. Behavioral Segmentation
8. Executive KPI Reporting
9. Product Analytics Frameworks
10. Experimentation Strategy
11. Business Recommendations

---

# Key Analyses

## Daily Platform Activity

Analyzed platform activity over time to understand customer engagement trends and identify periods of unusually high or low traffic.

<img width="635" height="372" alt="image" src="https://github.com/user-attachments/assets/76086b10-62ef-4ec9-b42e-2f3aac14cbb3" />

---

## Customer Conversion Funnel

Measured user progression from browsing products to adding items to the cart and ultimately completing purchases. Quantified conversion rates between each stage to identify the largest sources of customer drop-off.

<img width="483" height="421" alt="image" src="https://github.com/user-attachments/assets/570c43a1-e1eb-438f-9b05-7bfb91976f5b" />

---

## Category Performance

Compared purchase conversion rates across product categories to identify the highest-performing areas of the marketplace.

<img width="532" height="385" alt="image" src="https://github.com/user-attachments/assets/65695368-5ba5-47e7-845d-f6c612648e18" />

---

## Cohort Retention Analysis

Measured long-term customer retention by grouping users according to their first month on the platform and tracking subsequent activity.

<img width="594" height="424" alt="image" src="https://github.com/user-attachments/assets/1ae6d840-2d40-4094-9e77-f152d3c704c0" />

---

## Behavioral Segmentation

Segmented customers into Browsers, Cart Abandoners, Purchasers, and Power Users to better understand different behavioral patterns and identify opportunities for targeted interventions.

<img width="561" height="391" alt="image" src="https://github.com/user-attachments/assets/2fdf8e30-2f3e-4bb5-8dbf-fbfc787f2619" />

---

## Executive KPI Dashboard

Summarized the platform's primary business metrics, including acquisition, conversion, retention, and purchasing activity.

<img width="617" height="373" alt="image" src="https://github.com/user-attachments/assets/238632e0-f0b2-4fdc-8d78-86268bb2bda3" />

---

## Product Metrics Hierarchy

Organized platform metrics into a hierarchy linking raw user events to business goals through input metrics and the project's selected North Star Metric.

<img width="436" height="473" alt="image" src="https://github.com/user-attachments/assets/b960c19b-0530-4789-878d-eeb2c1315a1a" />

---

# Key Findings

- The largest opportunity for improvement occurs between **product views and cart additions**, where only **2.60%** of product views result in an item being added to the cart.
- Only **0.84%** of product views ultimately convert into purchases.
- Customer retention declines rapidly after the initial month, highlighting retention as the platform's primary long-term challenge.
- Cart Abandoners represent a valuable segment with high purchase intent but incomplete transactions.
- Power Users represent only a small fraction of customers but contribute disproportionately to long-term platform value.

---

# Business Recommendations

Based on the analyses performed throughout this project:

1. Improve product discovery and increase the View → Add-to-Cart Rate.
2. Reduce cart abandonment through checkout optimization and reminder campaigns.
3. Improve early customer retention through personalized onboarding and recommendations.
4. Develop retention strategies targeting high-value Power Users.
5. Validate proposed product changes through A/B testing before deployment.

---

# Skills Demonstrated

### SQL

- GROUP BY
- CASE WHEN
- JOINs
- CTEs
- Window Functions
- Aggregations
- Ranking
- DISTINCT

### Python

- pandas
- NumPy
- Matplotlib

### Product Analytics

- KPI Design
- North Star Metric
- Conversion Funnels
- Cohort Analysis
- Behavioral Segmentation
- Product Metrics Hierarchy
- AARRR Framework
- Experimentation Roadmap
- Guardrail Metrics

### Data Science

- Exploratory Data Analysis
- Data Cleaning
- Data Visualization
- Business Analytics
- Executive Reporting

---

## Techniques Used

- Data cleaning and preprocessing
- SQL joins, CTEs, window functions, and aggregations
- Exploratory data analysis (EDA)
- Conversion funnel analysis
- Product category performance analysis
- Cohort retention analysis
- Behavioral segmentation
- KPI and North Star Metric selection
- Product metrics hierarchy
- AARRR framework
- Experimentation roadmap
- Executive business recommendations

---

# How to Run

```bash
git clone <repository-url>

cd product-analytics-ecommerce

pip install -r requirements.txt

jupyter notebook
```

Download the RetailRocket dataset and place the CSV files inside the `data/` directory before running the notebook.

---

# Future Work

Potential extensions include:

- A/B Testing
- Customer Lifetime Value (LTV)
- Recommendation System Evaluation
- Predictive Modeling
- User Journey Analysis

These extensions would build upon the descriptive analyses presented in this project and further support product decision-making.
