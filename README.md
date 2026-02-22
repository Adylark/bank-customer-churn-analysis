<img width="1000" height="1000" alt="bank customer" src="https://github.com/user-attachments/assets/018a7a10-4bae-4edc-b394-d50a046d5835" />

# bank-customer-churn-analysis
End-to-end Power BI project to analyze customer churn behavior and identify key risk segments

## Business Problem
How can banks identify high-risk churn customers and what factors drive customer attrition?

## My Role
- Data Cleaning from messy dataset
- Transformation Data
- Star Scheme
- DAX Measure
- EDA
- Dashboard Design
- Business Insight

  ## Dataset
  https://mavenanalytics.io/data-playground/bank-customer-churn
  
  ## Data Preparation
  ### Data Cleaning
  - Change the data type to the correct one
  - Remove duplicate data
  - Handled null data or missing values

 ### Data Transformation
 - Created Age Group, Balance Group, Salary Group, Tenure Group for segmentation
 - Ensured churn column as binary numeric
 - Creation of various measures as needed to create appropriate visualizations

## Star Scheme
- Connecting the relationship between the two tables through the primary key CustomerId
- Setting cardinality as many-to-one and cross-filter direction

## Analyctical Questions
1. What is the overall churn rate?
2. Which age group has the highest churn rate?
3. Does owning more products reduce or increase churn risk?
4. Are inactive customers more likely to churn than active customers?
5. Do high-balance customers churn less?

### Key Insight
1. Churn rate is at 20.38% (~1 in 5 customers) → this is a high level for retail banking
2.  - The age group 45–64 has the highest churn rate, reaching 48-50%, even though the number of customers is relatively small compared to the productive age group
    - Churn occurs at all levels of balance and salary, this indicates that the money factor is not the determining factor why they exited
3. Customers with 3-4 products actually have the highest churn, which could be because the product doesn't suit their needs
4. The majority of churn comes from inactive customers
5. There is no strong correlation between salary and balance with churn, but rather engagement plays a bigger role

### Recomendation
1. Not only focusing on acquisition, retention also needs to be considered in creating the program so that customers do not exit
2. - Offer products like wealth management, pension planning, term deposits for older customers
   - Don't rely solely on financial promotions (discounts, low interest rates, balance bonuses) to reduce churn, a more effective approach is to focus on engagement, digital experience, and product relevance
3. Evaluate the products offered and their cross-selling strategies, and also use personalized product recommendations
4. Develop strategies to reactivate dormant (inactive) customers, such as rewards for the first activity after a dormant period or personalized notifications
5. Retention strategies must shift from value-based segmentation (based on money/balance) to behavior-based segmentation (based on activity).
