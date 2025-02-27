Executive Summary
This project focuses on Exploratory Data Analysis (EDA) for Telco Customer Churn, leveraging NumPy, Pandas, Matplotlib, and Seaborn to clean, visualize, and extract insights from customer churn data sourced from Kaggle. The primary goal is to understand customer churn trends and the factors influencing retention.

🔍 Key Analysis and Insights (with Percentages)
1️⃣ Data Cleaning & Preprocessing:
Blank values were replaced with 0, and necessary columns were converted from object to float.
The SeniorCitizen column was converted from (0,1) to ("Yes", "No") for better readability.
2️⃣ Customer Churn Rate Analysis:
26.54% of customers have churned, highlighting a significant retention challenge.
Churn is highest among customers on month-to-month contracts, suggesting that longer commitments reduce churn risk.
3️⃣ Impact of Services on Churn:
Tech Support Absence: Customers without Tech Support had a significantly higher churn rate than those who had support.
Internet Service Type:
Fiber Optic users churned at a rate of ~40%, significantly higher than DSL users (~25%).
This indicates potential dissatisfaction with Fiber Optic service or pricing concerns.
Paperless Billing & Online Security: Customers with Paperless Billing and no Online Security had higher churn rates than those using traditional billing and security services.
4️⃣ Contract Type & Churn Risk:
Month-to-month contracts had the highest churn rate (~43%), indicating that short-term customers are more likely to leave.
One-year contracts had a lower churn rate (~11%), while two-year contracts had the lowest churn rate (~3%).
This confirms that longer-term commitments reduce customer attrition.

📊 Business Implications
✔ Retaining short-term customers: Offering discounts or incentives for long-term contracts could reduce churn.
✔ Service Improvement: High churn rates among Fiber Optic users suggest a need to improve service quality or pricing models.
✔ Upselling add-ons: Customers without Tech Support or Security Services churn more—targeted cross-selling can improve retention.
✔ Paperless Billing Engagement: Churn is higher among paperless billing users, indicating a need for better digital engagement strategies.

🚀 Conclusion & Next Steps
This analysis provides actionable insights to reduce churn and enhance customer retention strategies. The next steps include:
✅ Building predictive churn models using machine learning.
✅ Developing targeted marketing campaigns for at-risk customer segments.
✅ Exploring additional customer behavior data for deeper insights.
