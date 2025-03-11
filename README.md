# Customer Churn Analysis

## Introduction
This analysis explores customer churn behavior using a dataset containing customer details, subscription information, and churn status. The objective is to identify key factors influencing churn and provide actionable insights.

## Data Preparation
- The dataset was examined for missing values and inconsistencies.
- Blank values in the `TotalCharges` column were replaced with `0` and converted to float.
- The `SeniorCitizen` column was encoded as 'Yes' or 'No' for better readability.
- Duplicate customer IDs were checked and confirmed to be unique.

## Exploratory Data Analysis (EDA)
### Churn Distribution
- A count plot and a pie chart illustrate the proportion of churned vs. retained customers.
- Approximately **26% of customers have churned**, while **74% remain active**.

### Feature Insights
- Count plots were generated for categorical variables (e.g., `PhoneService`, `InternetService`, `TechSupport`).
- Each feature was analyzed to observe trends among churned and retained customers.
- **OnlineSecurity and TechSupport**: Around **50% of customers** without online security or tech support have churned, compared to only **15-20%** of those with these services.
- **Internet Service Type**: **Fiber optic users have a churn rate of 42%**, significantly higher than DSL users at **23%**.
- **Senior Citizens**: **Churn rate among senior citizens is 35%**, compared to **24%** for non-senior customers.
- **Streaming Services**: Customers who use streaming TV and movies have a slightly **higher churn rate (30%)** compared to non-users **(22%)**.

## Key Findings
- Customers with **no tech support or online security** are more likely to churn.
- **Fiber optic internet users** exhibit a **1.8x higher churn rate** compared to DSL users.
- **Senior citizens** tend to have a **46% higher churn rate** than younger customers.
- **Multi-line phone service and streaming services** show a correlation with churn behavior.

## Conclusion and Recommendations
- **Bundled security services** may help retain customers.
- **Retention strategies** should be designed specifically for fiber optic users.
- **Personalized engagement strategies** can help reduce churn among senior citizens.
- **Optimized subscription plans** can encourage long-term commitments.
