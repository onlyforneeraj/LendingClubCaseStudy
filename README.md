# Project Name
> Lending Club Case Study: Lending Club is a marketplace for loans where borrowers apply for loan, investors may/may not provide the loan.
> Objective of the project is to analyse the existing data of defauts and non defalts, and provide recommendations to investors so that 
> they can decide on whether to sanction loan for next applicaant or not.


## General Information
- Lending Club is a marketplace for loans. Borrowers apply for loan. Investors decide whether to approve the loan. If a loan is given to an applicant, he/she might repay with interest rate or may default.
- When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.

Two types of risks are associated with the club’s decision: 
1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company. 
2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

- Investors face probelm in deciding whether to provide loan for a applicant or not. If they sanction loan for an appliant who is most likely to default then they will lose the money. If they do not provide loan for an applicant who is likely to repay then again it will be loss for the investor.

- Dataset used: loan.csv


## Conclusions
- Largest percentage of defaults happend in loans issued in year 2007. Number of Loans approved are increasing every year. Pecentage of charged off loan is stagnant around 15% for last three years.

Conclusions for Loan attributes:
- Percentage of defaults in loans having 60 months term is almost double of 36 months term. Club should negotiate for smaller term repayments for its loan.
- Going by the purpose of the loan, default in small business loans is highest followed by loans taken for 'renewable energy'.
- Larger percentage of default customer's loan interest rate was between 15% to 24%
- Customers whose purpose of loan is small_business had large ticket loans as compared to other categories. other than loan purpose of type 'home'.
- Larger percentage of default is in loan category grade as 'G' and 'F'
- Grade 'F' loans are defaulting at the higher loan amounts ,charged off loans median = $18000, while fully paid loans have the median of approx $15000 median of charged off loans for remaining grades is either same or lower than the median of fully paid off loans.

Conclusions for customer attributes:
- Going by the percentage of default customers, Nebraska has the highest rate of default (~ 60%).
- Approximate 40% of default customers have two public bankrupcies.
- Customers who have a mortgage loan are least likely to default.
- Largest percentage of loan defaults are from customers whose home_ownership category is Other.

- Customers who have taken more loans with high interest rate for debt consolidation have high default rate.






## Technologies Used
- Pandas - version 1.1.5
- Python - version 3.6
- matplotlib - version 3.3.4
- seaborn - version 0.11.2


## Acknowledgements
- This project is an assigment by Upgrad and IIIT-B as a part of Exploratory Data Analysis


## Contact - feel free to contact us
Chaitra Hegde
Neeraj Kumar

