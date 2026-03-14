# Telecom-Churn-Analysis

![](https://github.com/Chet-Dav/Telecom-Churn-Analysis/blob/main/cust%20churn%20pics.png)


## Introduction:

In the telecommunications industry, customer retention is a critical factor that directly impacts long-term profitability and growth. Acquiring new customers is significantly more expensive than retaining existing ones, making it essential for companies to understand why customers leave and what factors influence their decisions.

This project focuses on analyzing telecom customer data to uncover patterns behind customer churn. Using an interactive Power BI dashboard, the analysis examines customer service interactions, subscription plans, usage behavior, and account tenure to identify key drivers of churn. By transforming raw telecom data into actionable insights, this analysis helps highlight high-risk customer segments and provides a foundation for improving retention strategies.

## Key Metrics:
1. What is the relationship between customer service calls and customer churn?
2. Is there a threshold of service calls that indicates a high churn risk?
3. How do subscription plans such as International Plan and Voice Mail Plan influence churn?
4. Does customer tenure affect the likelihood of churn?

## Skills/Concepts demonstrated:

The following Power BI and data analytics concepts were applied:
- Data Cleaning & Transformation (Power Query)
- DAX Measures (Churn Rate, ARPU, Call Averages)
- Data Visualization & KPI Design
- Slicers and Interactive Filtering (Tenure, State, Plan types)
- Geographic Mapping (Visualizing metrics across Area Codes and States)

## Visualization and Analysis:
![](https://github.com/Chet-Dav/Telecom-Churn-Analysis/blob/main/Churn%20Dashboard%201.png)
![](https://github.com/Chet-Dav/Telecom-Churn-Analysis/blob/main/Churn%20Dashboard%202.png)

### Analysis:
### What is the relationship between customer service calls and customer churn?

The analysis clearly shows a direct relationship where increasing service frequency leads to higher attrition. While customers with 0 to 2 calls have a churn rate of only 10-14%, those who reach 4 calls see their risk triple to 48%. This demonstrates that repeated service interactions are a primary predictor of churn, reaching a 100% loss rate for customers who call 8 or more times.

### Is there a threshold of service calls that indicates a high churn risk?

The data identifies 4 calls as the "tipping point" for customer dissatisfaction. The tenure distribution and churn status charts confirm that as the number of calls increases, the volume of loyal customers drops sharply. This identifies a critical window for intervention. If a customer's issue is not resolved within 3 calls, they enter a high-risk category where they are significantly more likely to leave.

### How do subscription plans influence churn?

There is a massive disparity in churn based on plan type. The International Plan is a high-risk segment with a 43.7% churn rate, suggesting the plan may be overpriced or underperforming compared to competitors. Conversely, the Voice Mail plan acts as a retention anchor. Customers with this plan have a churn rate of only 8.87%, compared to 16.71% for those without it.

### Does customer tenure or usage volume affect the likelihood of churn?

The analysis reveals that Orange Telecom is actually losing its most "valuable" customers. Churned customers have a higher average revenue ($64.84) and higher total day minutes than loyal customers. While the average account length is 100 months, the dashboard indicates that high-usage customers are more sensitive to service issues and are likely the ones most actively seeking better value elsewhere.

You can view my interactive Dashboard [HERE](https://github.com/Chet-Dav/Telecom-Churn-Analysis/blob/main/Orange%20Telecom%20Churn%20Analysis.pbix)


## Conclusion and Recommendation:
Overall, this analysis proves that a significant number of high-value customers are leaving because their technical or service issues aren't being resolved during their initial calls. While the general churn rate sits at 14.55%, the massive loss of customers using the International Plan and those calling support multiple times represents a major hit to the company's most profitable accounts. To stop this trend, the business must prioritize faster problem resolution and a complete rethink of how their premium plans are priced and delivered.

To mitigate this losses, the company should start by using a three-call rule where any customer reaching their third support interaction is automatically moved to a senior specialist to ensure the problem is fixed before they decide to leave. There is also a clear need to review the International Plan to either lower the cost or add better features that stop people from canceling at such a high rate. 

Additionally, pushing Voice Mail adoption through small rewards or discounts is a smart move since the data shows these users are much more likely to stay loyal. Finally, offering special retention deals to customers with high daily usage will help ensure these top-tier spenders don't feel the need to switch to a competitor.


## Connect with me:
[LinkedIn](www.linkedin.com/in/michael-ohiachetachi)













