# STATISTIC ANALYSIS ON ONLINE SHOPPING DATA

This report evaluates the data of an online shopping portal data. The report's dataset is taken from the year 2020. 
The methods used to determine a relationship between the variables are linear regression, Pearson's Correlation, and 
the t-test. To support the observations, graphs such as the box plot, bar chart, Q-Q plot, and histogram have been applied.

The count of orders from different states and regions for different categories is presented using the bar chart. The 
frequency distribution of profit percentage is visualized with the help of a histogram. While exploring the associations 
between variables, the impact of offered discount on sales istested using the hypothesis testing, the Pearson's correlation 
value of 0.53 indicated that there is a significant positive association between sales and profit. Last, the regression 
model may be utilised to estimate the profit with the help of other variables

The subsequent questions will be addressed in this analysis report.
Q1. Do sales change when the discount is offered? 
Q2. What is the relationship between sales and profit?
Q3. From which state retailer receives the most orders?
Q4. Which shipping mode customer prefers most?
Q5. Which category of product is most in demand?
Q6. From which region retailer receives the most orders?

Data Set Used : United States e-commerce records (https://www.kaggle.com/datasets/ammaraahmad/us-ecommerce-record-2020)
This is a public dataset of orders placed on an e-commerce website in the United States. The 
dataset contains information on over 3000 orders placed through an online portal in the year 
2020 and contains 15+ columns. Its features enable to see an order from different dimensions: 
from order details, when a customer ordered, shipment mode for order, ordered from which 
region, city and state and postal code, Categories and subcategories of products, Quantity of 
products in order, how much discount applied and how much profit gained from the sale.

DATA PRE-PROCESSING :
i. Country column has been removed because all record has a common country so it’s not 
going to help for any kind of statistic. 
ii. Added column with calculated profit percentage to get an insight of profit in the form of 
a percentage. 
iii. “Product name” and “Row ID” columns have less relevance so removed
iv. City and State column are present, so removed Postal Code
v. Added column to indicate Boolean status for Discounted/Not Discounted for hypothesis 
testing.
vi. Removed outliers where profit percentage is -100+
