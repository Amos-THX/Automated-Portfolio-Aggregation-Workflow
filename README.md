![alt text](https://github.com/Amos-THX/Portfolio-Aggregation/blob/main/portfolio_performance_report.png?raw=true)

## Overview

This project demonstrates how transaction data, portfolio holdings, and market price data can be combined to build an automated portfolio reporting pipeline powered by Large Language Models (LLMs).

By integrating portfolio transactions with real-time market data from Yahoo Finance, the data pipeline generates concise and insightful daily portfolio summaries automatically.

The project showcases how modern data engineering workflows and LLMs can be leveraged to transform raw financial data into human-readable investment insights.

## Features
- Automated ingestion of portfolio transaction data
- Portfolio return and performance calculations
- Market benchmark comparison
- Integration with Yahoo Finance price data
- End-to-end report generation workflow


```
Transaction Data
        │
        ▼
Market Price Retrieval (Yahoo Finance)
        │
        ▼
Portfolio & Holdings Calculation
        │
        ▼
Performance Metrics + Benchmark Returns
        │
        ▼
Automated Daily Portfolio Report
```


## Technologies Used
- Python
- Pandas
- Yahoo Finance API (yfinance)
- Matplotlib
- Jupyter Notebook

> **_[NOTE]_**
>  While the prototype is demonstrated using Pandas for simplicity and rapid development, the data pipelines can also be implemented using PySpark for large-scale production workloads.

### Transaction Data

### Market Price Retrieval

### Portfolio & Holdings Calculation

### Performance Metrics + Benchmark Returns

### Automated Daily Portfolio Report


## Notebook
[Github Link](https://github.com/Amos-THX/Automated-Portfolio-Aggregation-Workflow/blob/cf0e679da08639bcbcbf5b2b535925f25acac34d/Portfolio_Aggregator.ipynb)

