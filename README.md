# Mavenflix-Subscription-Growth-Revenue-Intelligence

## Project Objective

To analyze Mavenflix’s subscription lifecycle, revenue performance, customer retention, and churn behavior to uncover growth patterns and actionable business insights.


## Dataset

https://github.com/anmolsodhi848-wq/Mavenflix-Subscription-Growth-Revenue-Intelligence/blob/main/Subscription%20Cohort%20Analysis%20Data.xlsx


## Key Performance Indicators (KPIs)

1. **Total Customers**: 2,877
2. **Active Subscriptions**: 1,065
3. **Net Subscriber Growth**: 939
4. **Retention Rate**: 32.6%
5. **Total Revenue**: $114,504


## Process

1. **Data Cleaning (Excel)**
   1. Standardized date formats
   2. Created subscription duration (in months)
   3. Identified churned vs active customers
   4. Derived retention and growth metrics

2. **Feature Engineering**
   1. Created duration bins (0–1, 1–3, 3–6, 6–12, 12+ months)
   2. Calculated Net Subscriber Growth
   3. Computed Monthly Revenue Trends
   4. Built ARPU by Payment Status

3. **Data Visualization (Tableau)**
   1. KPI Cards (Executive Summary View)
   2. Monthly Revenue Trend Line
   3. Churn Trend Analysis
   4. Revenue by Subscription Status
   5. Revenue by Payment Status
   6. Subscription Lifecycle Distribution


## Dashboard

<img width="1641" height="795" alt="image" src="https://github.com/user-attachments/assets/05cef6ab-c58f-41ca-8235-7e974beddba2" />


## Project Insights

1. **Subscription Trend Over Time**

Mavenflix subscriptions grew steadily from late 2022 to mid-2023, reflecting strong acquisition momentum, but growth became more volatile in later months as churn spikes began to impact net growth; revenue mirrored this pattern, rising to a mid-2023 peak before a sharp decline in the most recent month, likely due to seasonal churn or incomplete monthly data.

2. **Long-Term Subscription Behavior**

Approximately 37% of customers remain subscribed for five months or more, indicating moderate customer stickiness and strong initial acquisition; however, the large concentration of customers in the 0–3 month range highlights weak early retention and suggests that early-stage churn is a key business challenge.

3. **Monthly Retention Performance**

Retention was strongest in early 2023—particularly around March–April—when churn growth slowed, and active subscriptions peaked, while the weakest retention appeared in late 2023, where churn volume dropped sharply, likely due to incomplete cycle data or sudden cancellations; overall, the volatility indicates that subscription sustainability is still maturing.

4. **Revenue Distribution**

Cancelled subscriptions have generated more cumulative revenue than active ones, suggesting that many high-value users eventually churn, while paid subscribers deliver significantly higher ARPU than free users—highlighting the critical need to retain premium subscribers and strengthen long-term monetization strategies.

5.**Churn Trend**

Churn rose steadily through mid-2023 before declining sharply in the most recent period, potentially driven by subscription fatigue, pricing sensitivity, and a drop in content engagement.


## Conclusions

1. Mavenflix is experiencing strong customer acquisition but moderate retention weakness.
2. Roughly one-third of customers stay beyond 5 months, but early churn remains high.
3. Revenue growth is tied heavily to paid subscribers.
4. High-value customers eventually churn, reducing long-term revenue stability.
5. Retention peaked in early 2023 but weakened in later months.


## Recommendations

1. **Improve Early Retention (0–3 Months)**
   1. Onboarding campaigns
   2. Personalized content recommendations
   3. Discount incentives for  2–3 months

2. **Increase Long-Term Value**
   1. Introduce annual subscription plans
   2. Loyalty rewards for 6+ month subscribers
   3. Tiered pricing with premium benefits

3. **Reduce Premium Churn**
   1. Proactive cancellation surveys
   2. Targeted retention discounts
   3. Engagement-based remarketing

4. **Data-Driven Monitoring**
   1. Implement Cohort Analysis
   2. Track Monthly Retention Rate
   3. Monitor Churn by Subscription Interval


## Future Scope

1. Cohort retention modeling
2. Predictive churn analysis (Machine Learning)
3. Customer segmentation using RFM analysis
4. Lifetime Value (LTV) forecasting
5. Pricing elasticity testing


## Final Takeaway

Mavenflix has achieved strong acquisition momentum, but sustaining growth will require improving early retention and extending subscription duration beyond the 3–5 month window, as retention—not acquisition—is the primary lever for long-term revenue scalability.
