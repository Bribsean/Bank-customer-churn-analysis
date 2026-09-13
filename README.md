# Bank Customer Churn Analysis
## Project Overview

This Power BI project analyses 10,000 banking customers to understand customer churn patterns and identify customer segments associated with higher churn rates.

The analysis uses Power BI, DAX, data visualisation, and business-focused analysis to answer:

What customer characteristics and behaviours are associated with higher customer churn, and which customer segments should the bank prioritise for retention?

## Business Objective

Customer retention is an important challenge for financial institutions because losing customers can affect revenue, product adoption, and long-term customer relationships.

The objective of this project is to analyse customer data and understand the characteristics and behaviours associated with customer churn.

The analysis investigates customer churn across:

Customer demographics
Geography
Gender
Age groups
Number of banking products
Active membership
Credit card ownership
Card type
Customer tenure
Customer complaints and satisfaction

The dashboard is designed to help stakeholders identify customer segments that may require further investigation and potential retention strategies.

Important: This analysis identifies patterns and associations in the available data. It does not establish that any particular characteristic directly causes customers to churn.

## Business Questions

The dashboard was developed around the following business questions.

Overall Customer Churn
1. What is the overall customer churn rate, and how many customers have exited the bank?

This establishes the overall scale of customer churn within the dataset.

2. What proportion of the bank's customers have been retained compared with those who have exited?

This provides an overview of the retained versus churned customer population.

Customer Demographics
3. Which age groups have the highest customer churn rates?

Customers are analyzed across the following age groups:

18–29
30–39
40–49
50–59
60+

This helps identify whether churn is concentrated within particular age segments.

4. How does customer churn vary by gender?

The analysis compares churn patterns between:

Female customers
Male customers
5. Which countries have the highest customer churn rates?

The dashboard compares churn across:

Germany
Spain
France

This helps identify geographical markets where customer retention may require further attention.

## Customer Behaviour & Products
6. How does the number of banking products held by a customer relate to their churn rate?

The analysis compares customers with:

1 product
2 products
3 products
4 products

This is particularly important because the dashboard shows substantial differences in churn rates between product groups.

7. Is customer activity status associated with differences in churn rates?

Customers are compared based on whether they are:

Active members
Non-active members

This helps investigate whether customer engagement is associated with retention.

8. Does customer churn vary across different card types?

The dashboard compares:

Diamond
Platinum
Silver
Gold
9. Is there a difference in churn between customers with and without a credit card?

Customers are segmented into:

Credit card
No credit card
⏳ Customer Relationship
10. How does customer tenure relate to churn rates?

Customers are grouped into:

0–2 years
3–5 years
6–8 years
9–10 years

This helps determine whether newer or longer-standing customers show noticeably different churn patterns.

## Customer Experience
11. How does customer satisfaction relate to customer churn and complaints?

The dataset contains a satisfaction score from 1 to 5 and a complaint indicator.

The current dashboard specifically analyses complaint rate by satisfaction score. This allows the relationship between satisfaction levels and complaints to be explored.

A future enhancement would be to add churn rate by satisfaction score so that satisfaction can be directly compared against customer churn.

## Dashboard

The Power BI dashboard consists of two analytical pages.

### Page 1 — Executive Overview

The first page provides a high-level view of the bank's customer churn position.

Key KPIs:

| Metric             | Result |
| ------------------ | -----: |
| Total Customers    | 10,000 |
| Churned Customers  |  2,038 |
| Churn Rate         | 20.38% |
| Retained Customers | 79.62% |


The page also analyses:

Churn Rate by Age
Churn Rate by Gender
Churn Rate by Country
Churn Rate by Number of Products
Churn Rate by Active Membership

Interactive filters allow the dashboard to be explored by Age, Gender and Number of Products.

### Page 2 — Customer Behaviour

The second page provides deeper analysis of customer characteristics associated with churn.

It includes:

Churn Rate by Card Type
Churn Rate by Number of Products
Churn Rate by Credit Card Ownership
Churn Rate by Tenure Group
Complaint Rate by Satisfaction Score

## Key Insights
Overall Customer Churn

2,038 out of 10,000 customers have exited, resulting in an overall churn rate of 20.38%.

This means approximately 1 in 5 customers in the dataset has exited.

## Geography

Germany has the highest observed churn rate at approximately 32.4%, compared with:

Spain — 16.7%
France — 16.2%

This makes Germany an important segment for further investigation.

## Age

The 50–59 age group shows particularly elevated churn compared with several other age groups.

Rather than assuming age is the cause, this segment could be investigated further across geography, gender, membership status, product adoption and satisfaction.

## Number of Products

A significant difference appears across product groups:

| Products | Customers | Churn Rate |
| -------: | --------: | ---------: |
|        1 |     5,084 |      27.7% |
|        2 |     4,590 |       7.6% |
|        3 |       266 |      82.7% |
|        4 |        60 |     100.0% |

The 3- and 4-product groups have extremely high observed churn rates, but their customer populations are much smaller.

This highlights an important analytical principle:

A high percentage does not necessarily represent the largest business impact. The underlying population size must also be considered.

## Tenure

Churn rates across tenure groups are relatively similar:

0–2 years — 21.2%
3–5 years — 20.8%
6–8 years — 18.9%
9–10 years — 21.4%

This suggests that tenure alone may not be a strong differentiator of churn within this dataset.

## Card Type & Credit Card Ownership

The dashboard also investigates churn across different card types and credit-card ownership to determine whether these customer characteristics are associated with different churn patterns.

## Active Membership

The analysis compares active and inactive members to investigate whether customer engagement is associated with retention.

## Tools & Technologies
Microsoft Power BI
DAX
Data Analysis
Data Visualisation
Business Intelligence
Customer Segmentation
KPI Development
Data Modelling
Analytical Storytelling

## Dataset

The dataset contains 10,000 banking customer records.

Key variables include:

Customer ID
Credit Score
Geography
Gender
Age
Tenure
Account Balance
Number of Products
Credit Card Ownership
Active Membership
Estimated Salary
Churn/Exit Status
Complaints
Satisfaction Score
Card Type
Points Earned

The Exited field is used as the target variable:

0 = Retained
1 = Churned

## Future Improvements

Potential improvements to the analysis include:

Add Churn Rate by Satisfaction Score
Investigate combinations of churn factors, such as Age + Geography and Products + Membership
Add a Power BI Decomposition Tree for deeper exploratory analysis
Perform statistical testing to determine whether observed differences are statistically significant
Develop customer churn-risk segments
Introduce time-based analysis if suitable date information becomes available

## Dashboard Preview
### Executive Overview
![Executive Overview](Executive%20Overview.png)

### Customer Behaviour
![Customer Behaviour](Customer%20Behavior.png)



