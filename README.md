# Gold Price Prediction

## Project Overview
This project focuses on processing large-scale financial time series data to extract actionable trends and generate forecasting indicators. It implements machine learning algorithms to predict commodity price movements and analyze market trends using historical financial data.

## Data Sources
The primary dataset includes:
- Price trends calculated from financial time series data.
- Commodity prices including US Oil Fund (USO), Gold ETF (GLD).
- Stock market index data such as S&P 500 (SPX).

## Features Used
The model uses the following key features with their respective importance weights:

| Feature      | Importance Weight |
|--------------|-------------------|
| price_trend  | 0.9605            |
| USO          | 0.0264            |
| GLD          | 0.0075            |
| SPX          | 0.0056            |

The dominant feature in the prediction model is the calculated price trend.

## Machine Learning Approach
- The project uses **ensemble tree-based models** such as Random Forests or Gradient Boosting Machines to predict commodity prices.
- These machine learning models help capture nonlinear relationships in the data and assess feature importance for interpretability.
- Additional modeling techniques like linear regression or support vector regression might be used as baselines or complementary methods.

## Key Steps
1. Data preprocessing and cleaning of large-scale financial time series.
2. Feature engineering to generate meaningful indicators such as price trends.
3. Model training and evaluation using historical commodity and market data.
4. Interpretation of model results via feature importance scores.
5. Prediction of future commodity price movements based on trained models.

## Usage
- Load the dataset containing historical prices of commodities and market indices.
- Preprocess data with feature extraction for model input.
- Train machine learning models and evaluate their prediction accuracy.
- Use the trained model for forecasting and trend analysis.

## Conclusion
This project demonstrates how machine learning applied to financial time series data can provide valuable insights into commodity price dynamics and market trends. The combination of feature engineering and robust predictive modeling helps stakeholders make informed investment and trading decisions.

---

*For detailed implementation, refer to the project notebook and source code.*

