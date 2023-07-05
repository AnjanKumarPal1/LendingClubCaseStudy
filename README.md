# Lending Club Case Study
> To recommend a loan club company for approving the loans to its customers based on various EDA steps on a loan dataset.


## Table of Contents
* [Prerequisite & Objectives](#general-information)
* [Analysis Steps](#Data Analysis)
* [Python Libraries](#technologies-used)
* [Conclusions & Recommendations](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- When a person applies for a loan, there are two types of decisions that could be taken by the company:
Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

- This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
 
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
 
If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicant using EDA is the aim of this case study.
 
In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e., the variables which are strong indicators of default.  The company can utilize this knowledge for its portfolio and risk assessment. 
To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Lending club may reduce high rate for 60 months tenure, as those are susceptible to default. 

- It should check more data based on borrower grades (G to A) as it is a good metric for finding out defaulters. 

- Lending club should stop giving loans to borrowers with mortgage home ownership when loan amount requested is more than 12000 as they are likely to default approved loans after taking higher amount of loans. 

- Lending club should DTI records before giving loan to borrowers. 


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python library - numpy
- Python library - pandas
- Python library - matplotlib.pyplot
- Python library - seaborn
- Python library - Regular Expression re

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by MS program in AI/ML from IIITB and LJMU which is conducted by Upgrad as an assignment
- Risk Analysis site by Tibco "https://www.tibco.com/reference-center/what-is-risk-analytics"
- This project was based on [https://learn.upgrad.com/course/4617/segment/27462/164543/505323/2600603].
- Guidance and outline provided by Dr. Pooja Jain (Professor and Research Scholar at Indian Institute of Information Technology Nagpur)

## Contact
Created by [@AnjanKumarPal1] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->