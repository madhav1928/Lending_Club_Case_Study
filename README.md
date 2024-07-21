# Lending Club Case Study
> Assisting the largest online loan marketplace in identifying high-risk loan applicants to minimize credit loss.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
  
## General Information
### Background
This case study assumes the role of a consumer finance company specializing in urban lending. When processing a loan application, the company must decide whether to approve or reject the loan based on the applicant’s profile. Two main risks are associated with this decision:
Rejection Risk: Approving the loan could result in a lost business opportunity if the applicant is likely to repay.

The dataset includes information on past loan applicants, including whether they defaulted or not. The goal is to identify patterns that indicate an applicant's likelihood of default, which can inform decisions such as denying the loan, adjusting the loan amount, or applying higher interest rates.
 
In this case study, Exploratory Data Analysis (EDA) will be used to explore how consumer and loan attributes influence default risk.

Loan Decision Scenarios
When a loan is applied for, the company can make the following decisions:

- Loan Approved: Three scenarios can occur:
- Fully Paid: The applicant has repaid both principal and interest.
- Current: The applicant is still repaying the loan and has not defaulted.
- Charged-Off: The applicant has defaulted on the loan after missing payments for an extended period.
- Loan Rejected: The company rejects the loan due to unmet criteria. There is no available data on these applicants, as they did not proceed with the loan.
  
### Business Problem

As the largest online loan marketplace, the company offers personal, business, and medical loans with competitive interest rates through a quick online platform. However, lending to high-risk applicants poses a significant risk of credit loss, which occurs when borrowers fail to repay their loans.

Identifying these risky applicants is crucial for reducing credit loss. This case study aims to pinpoint the key indicators of loan default, allowing the company to enhance its risk assessment and portfolio management.


## Conclusions
Applicants with a loan term of 60 months are more likely to default.
Higher interest rate loans are associated with a higher likelihood of default.
Applicants with home ownership listed as “OTHER” have a higher default rate, while those with “NONE” show no defaults.
Surprisingly, income-verified applicants default more frequently, suggesting a possible issue with the verification process.
Loans for “educational” or “small business” purposes have a significantly higher default rate, between 8% and 17%.
Missing employment length data correlates with a higher default rate for 60-month loans.
Applicants with a 60-month term and verification statuses of “Source Verified” or “Verified” show higher default rates.
Applicants with no specified employment length and educational loan purposes have a higher default rate.

## Technologies Used
Python 3.x

### Python Libraries
- pandas - version 2.2.2
- matplotlib - version 3.8.4
- seaborn - version 0.13.2
