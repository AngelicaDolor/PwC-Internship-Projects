
# PhoneNow Call Centre Performance Dashboard

## Project Background

PhoneNow, a telecommunications company, operates a customer support call center, which handles customer inquiries across multiple departments. In Q1 2021, the company handled approximately **5,000 calls** across various customer needs such as streaming issues, technical support, payment-related questions, and administrative or contract-related inquiries. The purpose of this analysis is to provide insights into call center performance, agent productivity, and customer satisfaction to identify areas of improvement. This project was created in **Power BI**, analyzing **5,000 records** of call center data from January to March 2021.

### Key Business Metrics:
- **Total Calls Handled**: 5,000
- **Call Answer Rate**: 81.08%
- **Call Resolution Rate**: 72.92%
- **Average Answer Speed**: 67.52 seconds
- **Average Satisfaction Score**: 3.40 / 5.00
- **Abandoned Call Rate**: 18.92%
- **Unresolved Calls**: 27.08%

## Executive Summary

This dashboard provides an overview of the call center's performance for Q1 2021. Key findings include:
1. **High Call Volume and Peak Times**: Call volumes are highest at **1 PM daily**, with a notable spike on **Mondays**. This indicates a need for better staffing or system improvements to handle these peaks.
2. **Unresolved Calls**: **27.08%** of calls remain unresolved, with payment-related inquiries posing the biggest challenge. Targeted training or process adjustments in this area could significantly improve resolution rates.
3. **Agent Productivity**: While some agents perform exceptionally well (e.g., **Martha** and **Dan**), others like **Joe** may need additional support to improve answer times and customer satisfaction.

## Insights and Recommendations:

![Trend Analysis](https://github.com/AngelicaDolor/PwC-Internship-Projects/blob/main/trend-analysis.jpg)

### Category 1: Service Performance Metrics
1. **Customer Satisfaction**: The overall satisfaction score for Q1 2021 is **3.40**, peaking at **3.45** in January, which suggests a relatively moderate level of customer satisfaction. However, there’s room for improvement, especially during peak hours.
2. **Abandoned Calls**: **18.92%** of calls were abandoned, mainly during peak hours (11 AM - 1 PM). This indicates that customers are either waiting too long or facing system issues, which affects customer satisfaction.
3. **Unresolved Calls**: **27.08%** of calls were not resolved, with the highest number of unresolved calls coming from **payment-related** issues. This suggests a need for targeted training or system enhancements for handling payment inquiries.

### Category 2: Call Volume Insights
1. **January Peak**: Call volume peaked in January, with **1,772** total calls (9.79% higher than February and March). This aligns with post-holiday support demand.
2. **Peak Hours**: Call volume spikes at **1 PM daily**, with the highest volume of calls received on Mondays, potentially indicating the accumulation of unresolved issues over the weekend.
3. **Payment Issues**: Payment-related inquiries received the highest number of unresolved calls, indicating potential inefficiencies in handling financial-related concerns.

### Category 3: Agent Performance
1. **Top Performers**: Agents like **Martha** and **Dan** have the highest call resolution rates (514 and 523 answered calls, respectively), coupled with above-average satisfaction ratings (3.47 and 3.45).
2. **Improvement Area**: Agents like **Joe** show lower satisfaction scores (3.33) and slower average answer speed (70.99 seconds), suggesting opportunities for process improvement or additional training.

## Data Structure & Initial Checks
The database analyzed contained **5,000 records** representing customer calls from January to March 2021. The data was pre-processed and validated before loading into Power BI for further analysis. Download Power BI Report [here](https://github.com/AngelicaDolor/PwC-Internship-Projects/blob/main/PWC_CallCentreAnalysis.pbix).

The DAX queries used to inspect and clean the data for this analysis can be found [here](https://github.com/AngelicaDolor/PwC-Internship-Projects/blob/main/call-centre-trend-analysis-DAX).

## Recommendations

Based on the findings above, the following recommendations can be made:
1. **Improve Payment Inquiry Handling**: Target training for agents on handling payment-related calls to reduce unresolved cases.
2. **Optimize Staffing for Peak Hours**: Since call volumes peak at **1 PM** and on **Mondays**, adjusting staffing levels during these times could reduce abandonment rates and improve overall service levels.
3. **Monitor Agent Performance**: Implement performance improvement plans for agents with lower satisfaction scores and slower response times to ensure consistent service quality across the team.
4. **Reduce Call Abandonment**: Investigate system improvements or offer callbacks for high-traffic periods to reduce the **18.92%** call abandonment rate, especially during peak hours.

## Assumptions and Caveats
- The analysis assumes that the **5,000 calls** represent a complete dataset for Q1 2021.
- Peak hours and call volume trends are assumed to be consistent based on the available three months of data.
- Customer satisfaction scores were based on a scale of 0 to 5, with 3.40 as the average score.
