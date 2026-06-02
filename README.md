# Serverless Cloud Cost Optimization & Predictive Analytics Platform

## Project Overview

This project analyzes serverless cloud infrastructure metrics and predicts cloud execution costs using Machine Learning. The solution helps identify cost drivers, optimize resource utilization, and provide actionable insights through interactive Power BI dashboards.

---

## Problem Statement

Organizations using serverless cloud services often face unexpected execution costs due to inefficient resource utilization, high invocation rates, and performance bottlenecks.

This project aims to:

- Analyze cloud function metrics
- Predict execution costs
- Identify optimization opportunities
- Monitor performance through dashboards

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- PostgreSQL
- Power BI
- Git & GitHub

---

## Dataset

The dataset contains serverless cloud function metrics including:

- Function Invocations
- Execution Duration
- Memory Usage
- Error Rate
- Concurrent Executions
- Execution Cost

---

## Data Analysis

Performed:

- Data Cleaning
- Missing Value Handling
- Exploratory Data Analysis (EDA)
- Feature Engineering
- KPI Generation

---

## Machine Learning Model

### Model Used

Random Forest Regressor

### Objective

Predict cloud execution cost based on serverless infrastructure metrics.

### Workflow

1. Data Preprocessing
2. Feature Selection
3. Model Training
4. Cost Prediction
5. Result Evaluation

---

## Power BI Dashboard

The dashboard includes:

### Executive Overview
- Total Cost Analysis
- Average Runtime
- Resource Consumption

### Actual vs Predicted Cost
- Cost Prediction Accuracy
- Variance Analysis

### Performance Dashboard
- Runtime Efficiency
- Memory Utilization
- Invocation Trends

### Cost Optimization Dashboard
- High-Cost Functions
- Resource Optimization Insights

### Recommendation Dashboard
- Cost Reduction Suggestions
- Performance Improvement Opportunities

---

## Project Structure

```text
CloudCostOptimization/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   ├── eda.ipynb
│   └── ml_model.ipynb
│
├── models/
│   └── cloud_cost_model.pkl
│
├── reports/
│   └── predictions.csv
│
├── screenshots/
│
├── dashboard/
│
├── sql/
│
├── README.md
```

---

## Dashboard Screenshots

### Executive Overview

![Executive Overview](screenshots/Executive%20overview.png)

### Actual vs Predicted Cost

![Actual vs Predicted Cost](screenshots/Actual%20vs%20Predicted%20Cost%20by%20Function.png)

### Cost Optimization

![Cost Optimization](screenshots/Cost%20Optimization.png)

### Optimization Recommendation

![Optimization Recommendation](screenshots/Optimization%20Recommendation.png)

### Performance Dashboard

![Performance Dashboard](screenshots/Performance%20Dashboard.png)

---

## Key Outcomes

- Predicted cloud execution costs using Machine Learning
- Identified major cloud cost drivers
- Built interactive Power BI dashboards
- Generated optimization recommendations
- Improved visibility into serverless resource utilization

---

## Future Enhancements

- Real-time cloud monitoring
- Automated alerting system
- Multi-cloud cost comparison
- Advanced forecasting models

---

## Author

**Deepika**

B.Tech Student | Data Analytics Enthusiast
