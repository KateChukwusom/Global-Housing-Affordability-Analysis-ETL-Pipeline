 #  Global Housing Market Data Pipeline

This project builds a scalable data pipeline to analyze housing affordability trends across countries using real-world economic indicators from 2013 to 2024. It combines modern data engineering tools like **Python**, **PostgreSQL**, **Apache Airflow**, and **Power BI** to deliver a complete data flow from ingestion to insights.

#  Project Objective

We designed and implemented an end-to-end data pipeline that ingests, cleans, transforms, stores, and visualizes housing market data to uncover trends in global housing affordability and economic influences over time.
This project analyzes the relationship between:
- Housing prices
- Rental costs 
- Economic indicators 

Key Questions:
- How did affordability ratios change between 2015-2019?
- Which economic factors correlate most strongly with price surges?
- Can we predict affordability crises using historical patterns?
- Designed for urban economists, policymakers, and data scientists, this toolkit transforms raw housing data into actionable insights.


# Tech Stack

| Tool           | Role                                        |
|----------------|---------------------------------------------|
| **Python**     | Data processing, transformation (Pandas)    |
| **PostgreSQL** | Relational database for structured storage  |
| **Airflow**    | Scheduling and orchestration of ETL tasks   |
| **Power BI**   | Data visualization and dashboarding         |
| **Jupyter**    | Exploratory data analysis and prototyping   |

# Dataset

- **Source:** Kaggle (pre-collected dataset)
- **Name:** Global Housing Market Extended
- **Time Span:** 2013 - 2024
- **Features Include:**  
  - `Country`, `Year`  
  - `House Price Index`, `Rent Index`  
  - `Affordability Ratio`  
  - `Mortgage Rate (%)`, `GDP Growth (%)`, `Inflation Rate (%)`  
  - `Urbanization Rate (%)`, `Construction Index`
