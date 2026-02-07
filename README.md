# Project Aim

The primary aim of this project is to empower stakeholders in the agricultural sector (farmers, traders, and government bodies) with data-driven insights. 

Specifically, it aims to:
1.  **Predict Market Prices**: Utilize machine learning to forecast the selling price of crops (specifically Millets and Oilseeds) based on various factors like location, season. This helps farmers make informed decisions about when and where to sell.
2.  **Forecast Demand**: Analyze market trends to predict future demand levels. This aids in supply chain optimization and helps prevent surplus or shortage scenarios.
3.  **Enhance Decision Making**: Provide accurate, algorithmic assessments of market conditions to improve profitability and market efficiency.

# Dataset Information

This repository contains datasets used for price prediction and demand forecasting of agricultural commodities, specifically millets and oilseeds.

## Data Source

The data was collected from **Agmarknet** (Agricultural Marketing Information Network), provided by the **Centre for Economic Data and Analysis (CEDA), Ashoka University**.

- **Source URL**: [https://agmarknet.ceda.ashoka.edu.in/](https://agmarknet.ceda.ashoka.edu.in/)

## Datasets Included

The `datasets/` directory contains the following files:

1.  **demand_forecasting_dataset.csv** (3,180 rows, ~373 KB)
2.  **price_suggestion_dataset.csv** (3,180 rows, ~268 KB)

These datasets are utilized in the following notebooks for analysis and modeling:
- `01_Price_Prediction.ipynb`
- `02_Demand_Forecasting.ipynb`

We utilize Machine Learning models to analyze the data and provide actionable insights.

### 1. Market Price Prediction Model
- **Algorithm**: Random Forest Regressor
- **Purpose**: To predict the selling price of crops based on historical patterns, location, and market conditions.
- **Model Accuracy**: **91.98%**

### 2. Demand Forecasting Model
- **Algorithm**: Random Forest Regressor (with Heuristic Demand Classification)
- **Purpose**: To forecast future demand levels using price trends, arrival quantities, and production estimates.
- **Model Accuracy**: **91.83%**
