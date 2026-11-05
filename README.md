# Sales-Forecasting
🛒 Retail Sales Forecasting using ARIMA, Prophet, XGBoost & LSTM
This project,focuses on forecasting daily retail sales using a range of classical time series and machine learning models to support better demand planning and inventory management.

🎯 Objective
Predict future daily product-level sales using different forecasting techniques and compare their performance to identify the most effective approach.

📂 Dataset
Source: https://www.kaggle.com/competitions/m5-forecasting-accuracy/data
Files used:
sales_train_evaluation.csv
calendar.csv
sell_prices.csv
🧠 Models Implemented
1️⃣ ARIMA — Traditional time series forecasting
2️⃣ Prophet — Facebook’s robust forecasting model
3️⃣ XGBoost — Gradient boosting with lag-based features
4️⃣ LSTM — Deep learning model for sequence prediction

🛠️ Project Workflow
Data preprocessing and merging from M5 dataset
Feature engineering (e.g., lag features for machine learning models)
Train-test split based on time series integrity
Model training and forecasting (30-day horizon)
Performance evaluation using:
MAE (Mean Absolute Error)
MSE (Mean Squared Error)
RMSE (Root Mean Squared Error)
R² Score
📊 Evaluation Summary
Model	MAE	MSE	RMSE	R² Score
ARIMA	0.82	1.13	1.06	-0.03
Prophet	29.42	1081.73	32.89	-1.55
XGBoost	3961.57	1.66e+07	4078.59	-16.39
LSTM	385.06	2.52e+05	501.57	0.76
✅ LSTM achieved the best performance with the highest R² score.

📈 Visualizations
Forecast vs Actual sales plots
Model performance comparisons
Prophet seasonality components visualization
🔔 Conclusion
LSTM emerged as the most accurate model for daily sales forecasting, highlighting the power of deep learning for time series prediction tasks.

🖥️ Tech Stack
Python, Jupyter Notebook
pandas, numpy, matplotlib, seaborn
statsmodels, prophet
tensorflow / keras, scikit-learn


⭐ If you found this project useful, feel free to ⭐ star the repository and connect for collaboration or feedback!
