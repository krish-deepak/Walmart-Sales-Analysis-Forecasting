# Walmart-Sales-Analysis-Forecasting

Project Objective
The goal of this project is to analyze the historical sales data of Walmart stores and build a predictive model to forecast weekly sales. The analysis aims to understand the impact of various external factors—such as store type, holidays, and macroeconomic indicators—on store performance, providing actionable insights for inventory management and business strategy.


Key Libraries Used
Data Manipulation: pandas, numpy

Data Visualization: matplotlib, seaborn

Machine Learning: scikit-learn

Methodology & Key Findings
The project followed a structured workflow, from data integration and cleaning to exploratory analysis and predictive modeling.

1. Data Integration & Preprocessing
Data Merging: The three separate datasets (stores, features, train) were merged into a single, unified DataFrame to create a comprehensive view for analysis.

Data Cleansing: Missing values in key macroeconomic features like CPI and Unemployment were handled using a median-based imputation strategy to maintain data integrity.

Feature Transformation: The Date column was converted to a proper datetime format, which was fundamental for all time-based analysis and feature engineering.

2. Exploratory Data Analysis (EDA)
The EDA phase focused on uncovering relationships between various features and weekly sales.

Store Performance: Analysis revealed a clear hierarchy in store performance. Type 'A' stores consistently generate the highest sales, followed by Type 'B' and 'C', confirming that store size and type are major drivers of revenue.

Impact of Holidays: Holiday weeks show distinct patterns. While some holidays like Thanksgiving and Christmas lead to significant sales spikes, others result in noticeable dips, providing crucial information for holiday-specific inventory planning.

Macroeconomic Correlation: The analysis explored the relationship between sales and macroeconomic indicators. It was observed that factors like CPI (Consumer Price Index) have a tangible correlation with sales figures, indicating that broader economic health influences consumer spending at Walmart.

3. Feature Engineering
To improve model performance, several new features were engineered from the Date column:

Temporal Features: Extracted Year, Month, Day, and WeekOfYear to allow the model to capture seasonality and time-based trends in the sales data.

4. Predictive Modeling
Model Development: A predictive model was developed to forecast Weekly_Sales. Based on your notebook, you experimented with regression models to predict future outcomes based on the prepared features.

Feature Importance: The model identified store size, type, and key temporal features (like month and week) as the most significant predictors of sales.

Model Evaluation: The model's performance was evaluated using standard metrics, demonstrating its capability to explain a significant portion of the variance in sales data. This provides Walmart with a reliable tool for forecasting demand.

Conclusion
This project successfully demonstrates an end-to-end data analysis workflow. By integrating multiple data sources, performing thoughtful EDA, and building a predictive model, we were able to identify the key factors driving Walmart's sales. The resulting insights and the forecasting model can directly support better business decision-making in areas like inventory management, marketing strategy, and resource allocation.
