# Project Name
Lending Club Case Study


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Contributors](#contributors)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This consumer finance company specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:<br><br>

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company<br>
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company<br><br>
 
The given data contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
In this case study, we will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.<br><br>

### - What is the background of your project?<br>
The project is based on Exploratory Data Analysis<br><br>

### - What is the business probem that your project is trying to solve?<br><br>
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.<br><br>Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.<br><br>

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.<br><br>

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.<br><br>

### - What is the dataset that is being used?
Downloaded the dataset from online student portal. It contains the complete loan data for all loans issued through the time period 2007 t0 2011.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Applicants whose annual income is lower, have the highest chances of loan defaults.
- Loan applications for  ‘small business’ and ‘renewable_energy’ as purpose tend to have the most       percentage of default cases.
- Loans with higher grades have highest percentage of loan defaults.
- Higher interest rates mean high chances of defaults.
- Similarly, higher Debt to income ratio means higher default cases.
- Loans of higher values have the highest percentage of default cases as well.
- Loans with loan term as 60 months have higher chances of default cases as compared to 30 months.
- We also saw that the loans which are verified only (and not income source verified) do have higher chances of loan defaults.
- One more point worth noting is that the loan applications in December have higher percentage of loan defaults. Again, this can be linked to verification of the loan applications. The loans are approved without proper verification since the organization wants to achieve their year end targets.
- We also saw that state can also be one deciding factor – States like ‘NV’, ‘TN’, ‘AK, ‘SD & ‘NM’ have higher default percentages.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Jupyter Notebook 6.4.5
- Numpy 1.20.3
- Pandas 1.3.4
- Matplotlib 3.4.3
- Seaborn 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contributors<br>
Atul Chauhan<br>
Sowmya Renukeshwara


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
