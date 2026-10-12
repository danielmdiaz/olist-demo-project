# Olist E-Commerce Analytics Project

**From Raw Data to Business Insights | Python · Pandas · Parquet · Power BI**

## Overview

This project explores the Brazilian e-commerce ecosystem using the publicly available Olist Brazilian E-Commerce dataset from Kaggle.

The goal is to build an end-to-end analytics workflow that transforms raw transactional data into structured, analysis-ready datasets and actionable business insights.

Using Python and Pandas for data preparation, Parquet as the analytical storage format, and Power BI for business intelligence and visualization, this project demonstrates a practical approach to working with real-world data.

The project covers the data preparation process, data quality assessment, exploratory data analysis, business metrics, and the development of an interactive dashboard.

**Project status:** In progress.

## Objectives

- Build a reproducible data preparation workflow using Python and Pandas.
- Load and explore multiple related e-commerce datasets.
- Assess data quality, identify inconsistencies, and handle missing values.
- Transform raw CSV files into efficient, analysis-ready Parquet datasets.
- Explore sales performance, customer behavior, product categories, and logistics.
- Analyze customer reviews and satisfaction indicators.
- Develop a Power BI dashboard to communicate findings through interactive visualizations.
- Document the technical workflow, analytical decisions, and business insights.
- Maintain a version-controlled and publicly accessible project on GitHub.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Data processing and analytical workflows |
| Pandas | Data manipulation, cleaning, and transformation |
| Parquet | Columnar storage for analytical datasets |
| PyArrow | Parquet reading and writing |
| Jupyter Notebook | Exploratory analysis and documentation |
| Power BI | Interactive dashboards and business intelligence |
| Git and GitHub | Version control, documentation, and portfolio publication |
| Linux | Data preparation and development environment |
| Windows | Power BI development environment |

## Project Architecture

The workflow separates data preparation from business intelligence, using Parquet as the interchange format between the Linux and Windows environments.

```text
Kaggle Dataset
      |
      v
Raw CSV Files
      |
      v
Python + Pandas
      |
      v
Data Quality & Transformation
      |
      v
Parquet Datasets
      |
      v
Power BI
      |
      v
Interactive Dashboard
      |
      v
Business Insights
```

The objective is to create a transparent and reproducible workflow in which data can be prepared and validated independently of the reporting layer.

## Dataset

**Source:** [Brazilian E-Commerce Public Dataset by Olist — Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The dataset contains anonymized information about orders placed in the Brazilian Olist marketplace. Its related tables cover different aspects of the e-commerce process, including:

- Orders and order status.
- Customers and geographic information.
- Products and product categories.
- Sellers.
- Payments and installments.
- Order items and prices.
- Shipping and delivery timestamps.
- Customer reviews.
- Product category translations.

These datasets make it possible to investigate relationships between commercial performance, customer experience, and operational efficiency.

*The dataset is used for educational and portfolio purposes. Refer to the original Kaggle source for its documentation and applicable terms.*

## Analytical Scope

The project will investigate several business domains.

### 1. Sales Performance

- Order volume and revenue trends.
- Sales distribution over time.
- Average order value.
- Payment methods and installment patterns.
- Order status and cancellation trends.

### 2. Customer Analytics

- Customer distribution across geographic regions.
- Customer purchasing patterns.
- Customer concentration and order frequency.
- Geographic differences in commercial activity.

### 3. Product and Seller Performance

- Product category performance.
- Revenue and order distribution across categories.
- Seller contribution to marketplace activity.
- Relationships between product characteristics and commercial performance.

### 4. Logistics and Delivery

- Estimated versus actual delivery times.
- Delivery performance and delays.
- Order processing and fulfillment timelines.
- Geographic patterns in delivery performance.

### 5. Customer Satisfaction

- Review score distribution.
- Customer ratings across product categories.
- Relationships between delivery performance and review scores.
- Potential operational factors associated with customer satisfaction.

The final metrics and analyses will depend on data quality, the relationships available between tables, and the findings obtained during exploration.

## Data Preparation Workflow

The data preparation process will follow these general stages:

1. **Data ingestion:** Load the original CSV files and