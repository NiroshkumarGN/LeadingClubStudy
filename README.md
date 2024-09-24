# Project Name
> Leanding Club Case Study


## Table of Contents
* General Info
* Technologies Used
* Conclusions
* Acknowledgements



## General Information
- Project Information
        This project involves analyzing loan default data to identify key factors that influence whether a borrower will default. By performing exploratory data analysis (EDA) on consumer and loan attributes, the aim is to uncover patterns that predict default risk. These insights can help a finance company make better decisions in approving loans, reducing credit loss, and optimizing lending strategies for higher-risk applicants. The ultimate goal is to minimize financial loss by identifying risky borrowers early in the loan approval process.

- background of your project
        The project focuses on a finance company that provides loans to urban customers. The company faces two major risks: losing business by rejecting applicants likely to repay, or incurring financial loss by approving loans for those likely to default. The goal is to use past loan data to identify key factors driving loan defaults, helping the company optimize its loan approval process and minimize credit losses.

- Dataset
        The dataset is a CSV file containing loan information from Lending Club, detailing various borrower attributes and loan performance outcomes. It includes data on whether loans were fully paid, are still active, or defaulted, providing key insights into the factors that influence loan repayment behavior and default risk.


## Analysis

 Univariate Analysis

   * The number of fully paid loans is significantly higher compared to loans that are either charged-off or still current.
   * Over half of the loans taken have a term of 36 months, in contrast to those with a 60-month term.
   * The interest rates are predominantly concentrated in the 5-10 and 10-15 ranges, with a noticeable dip around the 10% mark.
   * Most borrowers have more than 10 years of work experience.
   * Employees with over 10 years of experience are more likely to either default or fully repay their loans.
   * The majority of borrowers do not own property and are either on a mortgage or renting.
   * Approximately 50% of the borrowers are either company-verified or have their income source verified.
   * Annual income exhibits a left-skewed distribution, indicating that the majority of borrowers have relatively low incomes compared to the rest.
   * A significant portion of loans are taken for debt consolidation, followed by credit card repayment.
   * The highest number of defaults occurred when loans were issued in December. Additionally, loans issued in 2011 saw a higher default rate compared to other years.
   * Loans with a 36-month term are primarily composed of grade A and B loans, while loans with a 60-month term mostly consist of grade B, C, and D loans

Bivariate Analysis

   * Applicants with higher salaries predominantly applied for loans related to 'home improvement' 'house' and 'renewable energy'.
   * Borrowers in the $85k to $112k annual income bracket have the largest loan amounts.
   * Borrowers with a mortgage tend to have the highest annual income compared to other home ownership types
   * Employees with longer working history got the loan approved for a higher amount.
   * The verification status indicates that there are more verified loans, with a total amount of 189,663,350, compared to other statuses.
   * The majority of loan amounts are associated with a 36-month term, in comparison to a 60-month term.
   * The total fully paid amount, at 358,049,725, is significantly larger compared to the charged-off amount, indicating a higher proportion of successfully repaid loans.
   * The B grade loans, with an amount of 128,515.86, carry higher interest rates compared to other grades
   * The B grade loans, with a DTI of 156,264.41, have a higher debt-to-income ratio compared to other grades
   * Loan amounts increase with interest rates up to 17.5%, then decline, suggesting higher rates deter borrowing
   * The exponential increase in loans over the years suggests a significant rise in the debt-to-income (DTI) ratio, while the rate of loan defaults is decreasing.

## Conclusion

1) Loan Tenure and Default Risk: 
    * Loans with a 60-month term appear to be riskier compared to 36-month loans, as they include more B, C, and D grade loans, which are generally associated with higher interest rates and debt-to-income (DTI) ratios.

2) Income and Loan Behavior:
    * Borrowers with higher annual incomes tend to take out larger loans, especially for home-related improvements and renewable energy projects.
    * Despite higher incomes, the propensity to default seems higher in certain income brackets, such as the $85k to $112k range. Income alone isn't a perfect indicator of repayment capacity.

3) Employment and Risk:
    * Applicants with more than 10 years of work experience make up a large portion of both fully paid and defaulted loans, suggesting that work experience alone isn't a decisive factor in loan approval.
    * However, those with longer employment histories tend to be approved for larger loans, potentially leading to increased default risk due to higher financial burdens.
    
4) Interest Rate Impact: 
    * Loans with interest rates up to 17.5% are more common, but beyond this threshold, the number of loans decreases, implying higher rates may deter borrowers. However, these higher interest loans are riskier, as they are more likely to lead to default.

5) Debt-to-Income Ratio (DTI):
    * Higher DTI ratios, particularly in B grade loans, are correlated with increased loan amounts and default rates. This indicates that borrowers taking on larger loans relative to their income are at greater risk of default.

6) Homeownership and Borrower Risk:
    * Borrowers with mortgages tend to have higher incomes, but homeownership status (especially renting or mortgages) doesn't offer strong protection against default.
    * Non-homeowners and those renting may face additional financial pressures, making them more prone to default.
    
7) Verification Status and Loan Performance: 
    * Verified loans have higher total amounts, and a large number of fully paid loans fall into this category. This suggests that income verification might correlate with better repayment outcomes.

8) Loan Purpose and Default: 
    * Loans taken out for debt consolidation and credit card repayment make up a significant portion of both fully paid and defaulted loans. These loans may represent higher-risk borrowers attempting to manage existing debt, increasing their default likelihood.

9) Seasonal and Temporal Trends:
    * Loans issued in December have a higher default rate, potentially indicating seasonal financial strain or year-end budgetary issues for borrowers.
    * The year 2011 showed higher default rates, which could be reflective of macroeconomic conditions or specific changes in lending policies.
    
10) Increasing Loan Demand vs. Declining Default Rates:
    * Over time, the number of loans has increased, but default rates have declined, indicating possible improvements in lending practices or risk assessment strategies. However, the increase in the DTI ratio suggests rising financial pressure on borrowers.


## Technologies Used
    * Pandas
    * NumPy
    * Seaborn
    * MatplotLib
    

## Contact
Created by [@NiroshkumarGN/LeadingClubStudy] - feel free to contact me!

## Note 
Prashant was not involved in working on this case study.
