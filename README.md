# 📊 Superstore Sales Analysis (2014--2017)

A complete **end-to-end data analysis & predictive modeling project**
using the famous *Superstore* dataset.\
The goal: **find business insights** and **build models** that help
managers boost profit and growth.

------------------------------------------------------------------------

## 🚀 Project Highlights

-   **Exploratory Analysis (EDA)**
    -   Seasonality: December spikes, monthly/annual trends.
    -   Regional, state, and city-level sales & profit analysis.
    -   Category & sub-category performance (winners vs loss-makers).
    -   Customer-level deep dives (RFM segmentation, cohort retention).
-   **Business KPIs**
    -   Total Sales, Profit, Orders, Unique Customers.
    -   Average Order Value & Profit Margins by Category.
    -   Shipping time distribution & impact on customer experience.
-   **Customer Analytics**
    -   **RFM Analysis** → Champions, Loyal, Potential, At-Risk.
    -   **Cohort Analysis** → retention and re-engagement insights.
-   **Predictive Modeling**
    -   Features engineered: seasonality (Year/Month), discounts, unit
        economics, shipping time.
    -   **RandomForest Regressor** (baseline & tuned) vs **XGBoost**.
    -   Cross-validation with R² and RMSE metrics.
    -   Feature importance to understand key profit drivers.
-   **Forecasting**
    -   Holt--Winters Exponential Smoothing for 6-month sales forecast.
    -   Seasonal patterns captured for inventory & staffing planning.

------------------------------------------------------------------------

## 📈 Key Insights

-   **December** is consistently the top sales month.\
-   **West region** & **Technology category** dominate performance.\
-   Shipping time averages **\~3--4 days**; improving speed could drive
    retention.\
-   Loss-making sub-categories (e.g., Tables, Bookcases) need review of
    pricing & discounts.\
-   **XGBoost outperformed RandomForest** with the lowest RMSE (\~26 vs
    \~29).

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   **Python**: pandas, numpy, matplotlib, seaborn\
-   **Machine Learning**: scikit-learn, XGBoost\
-   **Time Series**: statsmodels (seasonal decomposition,
    Holt--Winters)\
-   **Visualization**: seaborn, matplotlib, WordCloud

------------------------------------------------------------------------

## 📂 Repository Structure

    📁 superstore-analysis
    │── Superstore_Analysis.ipynb   # Jupyter Notebook with full analysis
    │── README.md                   # Project documentation
    │── Sample - Superstore.csv     # Dataset (if allowed, otherwise Kaggle link)

------------------------------------------------------------------------

