# Telecom-Customer-Churn-Prediction
Predicting High-Value Customer Churn in the Telecom Industry

Project Overview
Customer churn is a major challenge in the telecom industry, where the annual churn rate is between 15-25%. Acquiring new customers is 5-10 times more expensive than retaining existing ones, making customer retention a business priority.

This project focuses on predicting churn among high-value customers using machine learning models. The goal is to enable telecom companies to take proactive retention measures before customers leave.

📊 Dataset Description
📅 Timeframe: Data spans four months (June–September).
🔑 Key Variables:

📶 Call Usage (incoming & outgoing minutes)
🌐 Internet Data Usage (2G/3G/4G)
🔄 Recharge Amounts
📍 Customer Location & Demographics
Churn is defined as customers who stopped using services (calls & internet) in the last month.

⚙️ Methodology
✅ Filter High-Value Customers: Identify customers above the 70th percentile of recharge amounts.
✅ Feature Engineering: Create predictive attributes using usage patterns & trends.
✅ Handle Class Imbalance: Use SMOTE, weighted loss functions to improve predictions.
✅ Model Selection: Train & evaluate Logistic Regression, Random Forest, XGBoost models.

🔍 Key Insights & Business Recommendations

📌 Top Predictors of Churn:

- Decline in recharge amounts over months.
- Reduced call & internet usage before churn.
- Lower engagement in the action phase.


📌 Retention Strategies:
✅ Personalized Retention Offers – Match competitor deals for at-risk customers.
✅ Early Intervention – Identify churn risks before they leave.
✅ Loyalty Rewards – Incentivize long-term customers.


🛠 Tech Stack
🔹 Python (Pandas, NumPy, Scikit-learn, XGBoost)
🔹 Data Visualization: Matplotlib, Seaborn
🔹 Machine Learning: Logistic Regression, Random Forest, XGBoost
🔹 Deployment (Optional): Streamlit

📜 License
This project is licensed under the MIT License.

📩 Contact
For any queries, feel free to reach out via GitHub Issues.






