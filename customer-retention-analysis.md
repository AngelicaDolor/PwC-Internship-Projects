# PhoneNow Customer Retention Analysis

### Project Background
PhoneNow is a telecommunications company operating in a competitive market, providing internet and phone services to both residential and business customers. The company faces high churn rates, particularly in customers using month-to-month contracts and fiber optic internet services. Retaining customers is crucial for reducing revenue loss and maintaining profitability. This project aims to analyze churn patterns using data from 7,043 customers, focusing on key factors influencing customer churn. The analysis was performed using Power BI, enabling the company to visualize trends and identify high-risk segments.

### Insights and recommendations are provided on the following key areas:
- Churn Trends and Risk Analysis
- Internet Service Type Influence on Churn
- Contract Type and Tenure Impact
- Customer Demographics and Billing Preferences

The DAX measures used for this analysis can be found [here](https://github.com/AngelicaDolor/PwC-Internship-Projects/blob/main/churn-analysis-dax).

### Data Structure & Initial Checks
The company’s data was structured as a single dataset containing 7,043 records and various customer attributes, including contract type, internet service, tenure, and billing methods. Key attributes include:
- **Churn Rate:** Customers who have stopped using PhoneNow services.
- **Contract Type:** Month-to-month, one-year, and two-year subscriptions.
- **Internet Service Type:** DSL, fiber optic, or none.
- **Billing Method:** Electronic check, mailed check, bank transfer, and credit card.

### Executive Summary
The analysis identified several trends that contribute to customer churn, highlighting specific risk factors:
1. **Contract type plays a major role** – Customers on month-to-month contracts are 6.32 times more likely to churn compared to those on longer-term contracts.
2. **Fiber optic users** have a higher churn rate than DSL users, representing 69% of the total churn population.
3. **Higher monthly charges and short tenures** increase churn rates, especially for customers paying more than $68 per month or with tenures of 0-5 months.

These insights suggest that churn is highly correlated with service type, contract length, and billing methods, giving the company actionable areas to target for retention.

**Risk Analysis Dashboard**
![Risk Analysis](https://github.com/AngelicaDolor/PwC-Internship-Projects/blob/main/risk-analysis-dashboard.png)

**Churn Dashboard**
![Churn Anaysis](https://github.com/AngelicaDolor/PwC-Internship-Projects/blob/main/churn-analysis-dashboard.png)

### Insights Deep Dive

#### 1. **Churn Trends and Risk Analysis**
   - **Insight 1:** The churn rate is 26.54%, with 1,869 customers having churned, leading to a monthly revenue loss of $139.1k. This affects total revenue, which is currently $16.06M.
   - **Insight 2:** A spike in churn is observed among customers with a **monthly charge above $68**, which aligns with higher service usage but also dissatisfaction with pricing.
   - **Insight 3:** **Month-to-month contracts** show significantly higher churn, indicating that longer contracts are more effective at retaining customers.

#### 2. **Internet Service Type Influence on Churn**
   - **Insight 1:** **Fiber optic service users** have the highest churn, representing 69% of churned customers. This service type is associated with higher technical tickets (73%) and potential service reliability issues.
   - **Insight 2:** Customers using **DSL service** show lower churn rates, which suggests fiber optic customers may experience issues with the service or find it too expensive.
   

#### 3. **Contract Type and Tenure Impact**
   - **Insight 1:** **Month-to-month contracts** result in a churn likelihood 6.32 times higher than customers with longer contracts. This indicates that offering incentives for long-term contracts could reduce churn.
   - **Insight 2:** Customers with a **tenure of less than 5 months** are 2.74 times more likely to churn. This suggests that early retention strategies, like loyalty programs or discounts within the first few months, could improve retention.
   

#### 4. **Customer Demographics and Billing Preferences**
   - **Insight 1:** 45% of churned customers use **electronic check payments**, which correlates with a higher churn risk. Paperless billing customers show a 75% churn risk, suggesting potential dissatisfaction with this billing method.
   - **Insight 2:** **Senior citizens** make up 25% of the customer base but show no significant increase in churn risk. However, **partnered customers** have a slightly higher churn risk, indicating a potential focus on household packages could help retention.
   

### Recommendations
Based on the insights above, the following actions are recommended:
1. **Target month-to-month customers** with retention offers such as discounts for switching to yearly contracts or offering loyalty rewards after 3-6 months of continued service.
2. **Address churn in fiber optic service** by improving service reliability and offering support for technical issues. This could be complemented with a targeted survey to understand the pain points.
3. **Incentivize customers with high monthly charges** (above $68) to stay by offering bundled services or promotional discounts.
4. **Improve customer experience during the first 5 months** to reduce early churn, such as offering personalized onboarding, better customer support, or discounts.
5. **Review paperless billing practices** to identify if customers using electronic checks face issues with the payment system. Offering alternative payment methods or incentives for switching billing preferences could reduce churn.

### Assumptions and Caveats
- **Assumption 1:** Missing customer demographic data (e.g., age, gender) was assumed not to affect overall churn patterns.
- **Assumption 2:** Data on monthly charges reflects total billing and may not account for promotions or discounts, which could slightly affect churn behavior.
- **Caveat 1:** Some technical support data was incomplete, which might under-represent the impact of service issues on churn for certain customer segments.
