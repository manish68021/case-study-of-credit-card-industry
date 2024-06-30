PSPD Bank Credit Card Operations Analysis
Business Problem:

PSPD Bank, operating in over 50 countries, aims to enhance decision-making in the credit card industry by analyzing and modeling data effectively. Mr. Jim Watson, the CEO, seeks to address issues related to bankruptcy, fraud, and collections and proactively respond to customer needs with appropriate offers and services.

Objective:
The objective of this analysis is to understand customer spending and repayment behavior using the provided datasets. This includes cleaning the data, performing necessary transformations, and generating summaries and insights.

Data:
The data is spread across multiple sheets in an Excel file:

Customer Acquisition: Details of customers at the time of card issuance.
Spend (Transaction data): Credit card spend for each customer.
Repayment: Credit card payments done by customers.
Credit Card Data: Details about credit cards.

Data Cleaning and Transformation:

Customer Age:
If age is less than 18, replace it with the mean age value.

Spend Amount:
If spend amount exceeds the limit, replace it with 50% of the customer’s limit.

Repayment Amount:
If repayment amount exceeds the limit, replace it with the limit amount.

Analysis and Summaries:

Distinct Customers:
Count the number of unique customers.
Distinct Categories:
Count the number of unique spending categories.
Average Monthly Spend:
Calculate the average monthly spend by customers.
Average Monthly Repayment:
Calculate the average monthly repayment by customers.
Monthly Profit Calculation:
Monthly Profit = Monthly Repayment - Monthly Spend.
Profit is earned only on positive profits with an interest rate of 2.9% per month.

Instructions:

Data Cleaning:
Ensure age is cleaned as per the criteria.
Adjust spend amounts and repayment amounts based on the provided limits.
Summarization:
Generate summaries for distinct customers, categories, average monthly spend, and average monthly repayment.
Calculate monthly profits and interest earned on positive profits.

Results:

Provide a detailed analysis and insights based on the cleaned data. Ensure to highlight key findings that could help PSPD Bank in strategic decision-making.

How to Run the Analysis:

Load the datasets.
Perform the necessary data cleaning and transformations.
Generate the required summaries and calculations.
Provide visualizations and insights based on the analysis.

Dependencies:

pandas
numpy
matplotlib

License:

This project is licensed under the MIT License.

