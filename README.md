# Retail-Market-Analysis

This repository contains the implementation and analysis for the **Retail Market Analysis** project, developed as part of the **Big Data Application Development Course**. The project leverages big data tools and technologies, including Apache Spark and Jupyter Notebooks, to analyze retail datasets (Amazon, Walmart, Instacart, and Google Trends). Insights into consumer behavior, seasonal trends, and product preferences were derived to inform better decision-making for inventory management, marketing strategies, and customer satisfaction.

## Repository Structure

### Preprocessing and Aggregation Code

1. **Amazon Preprocessing**:
   - **Files**:
     - `Amazon_preprocessing..ipynb`
     - `Amazon_preprocessing - Zeppelin.pdf`
     - `Amazon_preprocessing_2KCRHK9DV.zpln`
   - **Description**: Contains code for cleaning and preprocessing the Amazon reviews dataset, preparing it for analysis.

2. **Walmart Preprocessing**:
   - **Files**:
     - `Walmart_Data_Preprocessing - Zeppelin.pdf`
     - `Walmart_Data_Preprocessing_2KF9NF8NK.zpln`
   - **Description**: Preprocessing logic for Walmart sales data, focusing on handling missing data and ensuring consistency for downstream analytics.

3. **Amazon and Walmart Aggregation**:
   - **Files**:
     - `Amazon_And_Walmart_Aggregations - Zeppelin.pdf`
     - `Amazon_And_Walmart_Aggregations.ipynb`
     - `Amazon_And_Walmart_Aggregations_2KGM7YDV.zpln`
   - **Description**: Contains Spark-based aggregation logic to compute metrics such as weekly sales, monthly trends, and seasonal analysis across both datasets.

### Instacart Dataset Code

4. **Instacart Data Ingestion**:
   - **Files**:
     - `Instacart-data-ingestion.ipynb`
   - **Description**: Ingests and processes Instacart orders data, creating summaries and extracting temporal insights, such as order distribution by day of the week.

5. **Instacart Data Analysis**:
   - **Files**:
     - `Instacart-data-analysis.ipynb`
   - **Description**: Analyzes the processed Instacart dataset to explore purchasing trends and reorder behavior patterns.

### Percent Change and Trends

6. **Google Trends Data**:
   - **Files**:
     - `google_trends_data.zip`
   - **Description**: Includes Google Trends data for analyzing search trends related to retail and holiday seasons, correlating it with sales patterns.

7. **Percent Change Analysis**:
   - **Files**:
     - `percent_change_data.scala`
     - `percent_change_cleaning.scala`
     - `source code for percent change.zip`
   - **Description**: Implements percent change analysis in Scala to measure and visualize consumer activity fluctuations.

---

## Insights

This project yielded several key insights:
- **Seasonal Trends**: Gift card reviews and search trends peak during the winter holiday season, highlighting consumer behavior around gifting.
- **Weekly Patterns**: Instacart orders surge at the start of the week, while Amazon reviews peak midweek.
- **Holiday Impact**: Correlation between Google search trends and sales suggests increased consumer activity during holiday seasons.
- **Platform-Specific Behavior**: Different retail platforms exhibit unique patterns in terms of purchase and review timing.

---

## Technologies Used

- **Big Data Tools**: Apache Spark, Zeppelin
- **Programming Languages**: Python, Scala
- **Visualization**: Matplotlib, Zeppelin built-in visualizations
- **Datasets**: Amazon, Walmart, Instacart, Google Trends

---
