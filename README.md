# Lending Club Case Study
> Project Overview
Lending Club, a finance company who offers variety of loans to different customers with varying interests. As the number of loans given by this company keeps increasing the chances of loans not being paid off are also increasing. So, company should take decisions from the existing data to reduce the risk of loans getting defaulted.


## Table of Contents
* [Business Objective](#business-objective)
* [Recommendations from analysis](#recommendations-from-analysis)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## Business Objective
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. There will be risky customers who take loans and default it by not paying back.
By finding these risky customers company can reduce their Credit losses. Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In the data set , this type of similar behavior borrowers are labeled as “Charged-Off" who are responsible for the most significant losses to the company.
So, company wants to understand/know the variables behind this loan default, i.e. the variables which are strong indicators of default. 
The objectives of this EDA analysis is to help Lending Club in mitigating credit losses. We can see this in 2 ways:
	1) Identifying applicants likely to repay their loans as they are the ones who generate profits for the company through interest payments. So, rejecting such applicants would result in a loss of potential business.
        2) On the other hand, approving loans for applicants not likely to repay and at risk of default can lead to substantial financial losses for the company.


## Recommendations from analysis
As of the analysis performed we can derive few situations which lead to defaulting of loans mostly:
1) Borrowers with higher DTI should be considered as high risk of defaulting.
2) Borrowers taking loans for certain loan purposes like debt consolidation, credit card payments and
     same business are more likely to default.
3) The main factor od defaulting is interest rate, higher interest rate high chances of defaulting. So see
      that interest rates are reasonable.
4) Home ownership as mortgage have high chances of defaulting. And these borrowers take a huge
     amount as loan.
5) Borrowers having lower credit grades like E,F and G are more likely to default.
6) Longer loan term are associated with higher default rates.
7) Borrowers who are taking loans towards end of end year in Q4 are more likely to default.
8) A common notice as a whole is people who are taking big loans with high interest rate are mostly defaulting.


## Technologies Used
- [Python](https://www.python.org/) - version 3.10.12
- [Matplotlib](https://matplotlib.org/) - version 3.8.4
- [Numpy](https://numpy.org/) - version 1.26.4
- [Pandas](https://pandas.pydata.org/) - version 2.2.2
- [Seaborn](https://seaborn.pydata.org/) - version 0.13.2


## Acknowledgements
This project was developed as a part of the Executive PG Programme in Machine Learning & AI at IIIT Bangalore.


## Contact
Created by :
  - [Varun Boya](https://github.com/varun138)
  - [Venkatesan Manivannan](https://github.com/venkemv)
