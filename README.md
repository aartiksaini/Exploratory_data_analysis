# Customer Churn Analysis

## Objective
The goal of this analysis is to identify factors influencing customer churn and derive actionable insights to improve customer retention. The process involves data cleaning, exploratory data analysis (EDA), and visualization to uncover key patterns and trends.

## Data Cleaning
- Removed duplicate entries.
- Handled missing values appropriately.
- Reformatted columns for consistency.
- Encoded categorical data for better interpretability.

## Exploratory Data Analysis (EDA)
- **Churn Rate:** Approximately **26.54%** of customers had churned.
- **Tenure Influence:** Customers with **1-2 months** of tenure are most likely to churn.
- **Contract Type:** Month-to-month contracts are a significant risk factor, while long-term contracts have a lower churn rate.
- **Service Usage:**
  - Customers using **DSL internet** and **online security services** were less likely to churn.
  - Customers subscribed to **streaming services** were more likely to leave.

## Visualizations
- **Pie Charts**: Show overall churn rate.
- **Count Plots**: Illustrate churn distribution across demographics.
- **Grouped Bar Charts**: Highlight trends in service usage and contract types.

## Key Findings
- **High-risk Groups:**
  - **Senior citizens** are more likely to churn.
  - **Month-to-month contract holders** have the highest churn rate.
- **Low-risk Groups:**
  - Customers with **long-term contracts** tend to stay longer.
  - Bundled services reduce the likelihood of churn.

## Retention Strategies
1. **Target Short-Tenure Customers:**
   - Offer onboarding incentives and personalized experiences.
   - Provide discounts on early billing cycles.

2. **Address Month-to-Month Contract Churn:**
   - Encourage long-term contracts with discounts and loyalty rewards.
   - Provide flexible upgrade options.

3. **Focus on Senior Citizen Retention:**
   - Simplify service packages and enhance customer support.
   - Offer exclusive discounts for senior citizens.

4. **Promote High-Retention Services:**
   - Bundle online security and DSL internet services with discounts.
   - Highlight benefits in marketing campaigns.

5. **Mitigate Churn in Streaming Service Users:**
   - Improve content recommendations and service quality.
   - Provide exclusive streaming perks.

6. **Proactive Customer Support:**
   - Identify at-risk customers using predictive analytics.
   - Engage with customers showing signs of churn.

7. **Loyalty and Rewards Programs:**
   - Introduce points-based rewards for long-term customers.
   - Recognize loyal customers through special offers.

8. **Flexible Payment Options:**
   - Allow customers to pause or adjust services.
   - Provide financial flexibility during difficult periods.

9. **Regular Customer Feedback Collection:**
   - Conduct exit and satisfaction surveys.
   - Use feedback to enhance customer experience.

## Tools & Libraries Used
- **Pandas & NumPy**: Data manipulation.
- **Matplotlib & Seaborn**: Data visualization.
- **Analytical functions**: Churn percentage calculation and customer segmentation.

## Impact
This analysis provides **data-driven insights** to help businesses **improve customer retention** by identifying high-risk groups and implementing effective engagement strategies.
