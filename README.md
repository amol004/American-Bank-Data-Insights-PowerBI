# FinInsight Group data analysis




[Bank final1.pdf](https://github.com/user-attachments/files/16741656/Bank.final1.pdf)

### **Objective**

Your task is to employ Power BI to analyze these banking datasets, aiming to unravel the intricate patterns and behaviors within the data. This involves in-depth data cleaning, robust data modeling, and strategic use of DAX for complex analytics. Your goal is to create a comprehensive, interactive dashboard that not only illustrates transactional trends and customer profiles but also offers a holistic view of the banking ecosystem. This analysis should include understanding customer transaction behaviors, identifying relationships between account characteristics and financial health, and exploring factors influencing credit scores and loan management. Your insights will guide FinInsight Group in advising banking institutions on optimizing their services, enhancing customer satisfaction, and managing financial risks effectively.

The "BankingDataset1.xlsx" file contains the following columns:

1. **TransactionID**: A unique identifier for each transaction. 
2. **AccountNumber**: The account number associated with the transaction. (Foreign Key)
3. **TransactionType**: The type of transaction (e.g., Transfer, Deposit, Withdrawal, Payment).
4. **Amount**: The amount of money involved in the transaction.
5. **TransactionDate**: The date when the transaction occurred.
6. **BranchCode**: The code of the bank branch where the transaction took place.
7. **Currency**: The currency in which the transaction was made.
8. **TransactionTime**: The time of day when the transaction occurred (in hours).

The "BankingDataset2.xlsx" file contains the following columns:

1. **AccountNumber**: A unique identifier for each account, corresponding to 'AccountNumber' in "BankingDataset1.xlsx". (Primary Key)
2. **AccountHolder**: The name of the account holder.
3. **AccountType**: The type of account (e.g., Credit, Loan, Checking).
4. **Balance**: The current balance of the account.
5. **InterestRate**: The interest rate applicable to the account.
6. **CreditScore**: The credit score of the account holder.
7. **OpeningDate**: The date when the account was opened.
8. **LoanAmount**: The amount of loan associated with the account (if applicable).
9. **AccountHolderDetails:** Details about account holders - employment sector, years at current residence, and city of residence etc.   



In this project, I leveraged Power BI to conduct a comprehensive analysis of banking datasets, focusing on 'Banking Transactions' and 'Customer Account Details.' Through meticulous data cleaning, robust data modeling, and strategic DAX utilization, I developed an interactive dashboard that visualizes transactional trends and customer profiles. This dashboard provides a holistic view of the banking ecosystem, offering actionable insights that guide financial institutions in optimizing their services, enhancing customer satisfaction, and effectively managing financial risks.


1.Comprehensive Data Analysis: Conducted in-depth analysis of 'Banking Transactions' and 'Customer Account Details' datasets, uncovering intricate patterns and behaviors critical to financial decision-making.

2.Data Cleaning & Modeling: Executed thorough data cleaning processes and implemented robust data modeling techniques to ensure the integrity and accuracy of complex banking datasets.

3.Strategic DAX Utilization: Applied strategic use of DAX for complex financial analytics, enabling detailed exploration of customer transaction behaviors and relationships between account characteristics and financial health.

4.Interactive Dashboard Development: Designed and developed a comprehensive Power BI dashboard that visualizes transactional trends, customer profiles, and provides a holistic view of the banking ecosystem.

5.Insightful Reporting: Delivered actionable insights through the dashboard, guiding banking institutions in optimizing services, enhancing customer satisfaction, and effectively managing financial risks.

6.Optimization of Banking Operations: Leveraged data-driven insights to advise FinInsight Group on strategies for improving banking performance, including customer relationship management and risk assessment.

# **Dashboard**

The Power BI dashboard features seven distinct visualizations that provide a holistic overview of banking transactions, customer data, and financial trends across various cities. Here’s a summary of each graph:

1.Count of Transaction Type (Pie Chart):

This pie chart displays the distribution of four transaction types: Deposit, Payment, Transfer, and Withdrawal. Each section represents the percentage of total transactions accounted for by each type, offering a quick insight into the most common transaction activities.

2.Median of Credit Score by Credit Score Category (Bar Chart):

This bar chart categorizes customers into three groups: Good, Average, and Poor, based on their median credit scores. The chart helps to assess the creditworthiness of different customer segments.

3.Sum of Loan by Year and City in USD (Bar Chart):

This bar chart breaks down the total loan amounts by year (2023, 2024, 2025) and city (Berlin, London, New York). It highlights the trends in loan disbursements over time and across different geographical locations.

4.Median of Amount, Loan Amount, and Credit Score by City and Account Type (Map with Bar Chart Overlay):

This map visualizes median amounts, loan amounts, and credit scores by city (Berlin, London, New York) and account type (Checking, Credit, Loan). The map is overlaid with bar charts, providing a geographical representation of financial health across regions.

5.Users and Their Credit Score Based on Account Type (Scatter Plot):

The scatter plot correlates users' credit scores with their loan amounts, segmented by account types (Checking, Credit, Loan, Savings). This visualization helps in understanding the relationship between account types and the financial behavior of customers.

6.Average of Interest Rate by City (Pie Chart):

This pie chart shows the average interest rate across different cities (Tokyo, Berlin, London, Sydney, New York). It provides insights into how interest rates vary geographically.

7.Count of High-Value and Normal Transactions Based on Cities (Bar Chart):

This bar chart compares the count of high-value transactions to normal transactions across various cities. It highlights the cities with the highest transaction volumes and the proportion of high-value transactions, which is essential for assessing financial activity in these regions.
Together, these visualizations offer a detailed analysis of banking transactions, customer behavior, and financial metrics, helping stakeholders make data-driven decisions.

![Bank final1_page-0001](https://github.com/user-attachments/assets/19d3bb59-d432-4f76-98e8-c0305b4e1612)
