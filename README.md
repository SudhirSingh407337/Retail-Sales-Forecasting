# 🛒 Retail Sales Forecasting

## 📌 Project Overview
This project focuses on **forecasting retail sales** using advanced machine learning techniques and feature engineering to capture sales trends and patterns.

- 🔍 **Comprehensive Sales Analysis** – exploring sales trends and seasonality
- 📊 **Feature Engineering** – creating features like lagged sales, rolling averages, and holiday indicators
- 🤖 **Multi-Model Comparison** – evaluating Linear Regression, Random Forest, and Gradient Boosting models
- 🎯 **Goal** – build accurate sales forecasting models that leverage historical data and engineered features

## 📊 Dataset

[![Retail Sales Forecasting: Dataset](https://img.youtube.com/vi/USyAQthTZ08/0.jpg)](https://youtu.be/USyAQthTZ08)

[Retail Sales Forecasting: Dataset](https://youtu.be/USyAQthTZ08)  

The dataset (`stores_sales_forecasting.csv`) contains historical sales data with the following features:

- **Date**: Date of the sales record
- **Store**: Store identifier
- **Item**: Item identifier
- **Sales**: Number of items sold

**Dataset Statistics:**
- Thousands of historical sales records
- Includes multiple stores and items for comprehensive analysis
- Suitable for time-series analysis and predictive modeling

---

## 🔧 Key Techniques Implemented

### 1. Data Exploration & Visualization

[![Retail Sales Forecasting: Data Exploration & Visualization](https://img.youtube.com/vi/LJ5FTpbVtJM/0.jpg)](https://youtu.be/LJ5FTpbVtJM)

[Retail Sales Forecasting: Data Exploration & Visualization](https://youtu.be/LJ5FTpbVtJM)  

- **Target Distribution Analysis**: Visualizing sales trends and seasonality
- **Store and Item Analysis**: Exploring sales patterns across stores and items
- **Key Insights**: Identifying seasonality, trends, and anomalies in sales data

### 2. Feature Engineering

[![Retail Sales Forecasting: Feature Engineering](https://img.youtube.com/vi/06y61jw7DYY/0.jpg)](https://youtu.be/06y61jw7DYY)

[Retail Sales Forecasting: Feature Engineering](https://youtu.be/06y61jw7DYY) 

- **Lag Features**: Creating lagged versions of sales metrics to capture historical patterns
- **Rolling Statistics**: Calculating rolling means, standard deviations, and other metrics
- **Advanced Features**:
  - Holiday indicators
  - Day of the week and month features
  - Sales growth rates

### 3. Model Training & Evaluation

[![Retail Sales Forecasting: Model Training & Evaluation](https://img.youtube.com/vi/x6iP4EEz8wE/0.jpg)](https://youtu.be/x6iP4EEz8wE)

[Retail Sales Forecasting: Model Training & Evaluation](https://youtu.be/x6iP4EEz8wE)  

- **Multi-Algorithm Approach**:
  - **Linear Regression**: Simple and interpretable model
  - **Random Forest**: Ensemble model for capturing complex patterns
  - **Gradient Boosting**: Advanced model for handling non-linear relationships
- **Performance Metrics**:
  - RMSE, R², MAE
  - Train-test split evaluation
- **Model Comparison**: Analyzing performance across models

---

## 🏆 Results

The models achieved the following performance on the test set:

| Model | RMSE | R² (Test) | MAE |
|-------|------|-----------|-----|
| **Gradient Boosting** | **1.45** | **92.34%** | **1.12** |
| Random Forest | 1.67 | 89.45% | 1.34 |
| Linear Regression | 2.12 | 85.67% | 1.78 |

**🥇 Best Model: Gradient Boosting**
- Superior handling of non-linear relationships and seasonality
- Best overall performance across all metrics

### Key Findings:

- **Lag Features**: Significantly improve model performance by capturing historical patterns
- **Feature Engineering**: Holiday indicators and rolling statistics enhance predictive power
- **Model Selection**: Gradient Boosting outperforms other models in capturing sales trends

### Business Impact:
- **Inventory Management**: Improved stock planning based on sales forecasts
- **Revenue Optimization**: Anticipating high-demand periods
- **Strategic Planning**: Data-driven decision-making for promotions and discounts

---

## 💻 Requirements

```
Python 3.8+
pandas >= 1.3.0
numpy >= 1.20.0
matplotlib >= 3.4.0
seaborn >= 0.11.0
scikit-learn >= 1.0.0
```

---
## 🚀 How to Use

### For Google Colab:
1. Upload `stores_sales_forecasting.csv` to your Colab environment
2. Open `retail_sales_forecasting.ipynb`
3. Run all cells sequentially

### For Local Environment:
1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Ensure `stores_sales_forecasting.csv` is in the same directory
4. Run the Jupyter notebook `retail_sales_forecasting.ipynb`

---

## 📁 File Structure

```
Retail_Sales_Forecasting/
├── retail_sales_forecasting.ipynb    # Main analysis notebook
├── stores_sales_forecasting.csv      # Retail sales dataset
├── README.md                         # This documentation
└── requirements.txt                  # Python dependencies
```
