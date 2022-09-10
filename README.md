# [Customer-Segmentation-in-the-US](https://github.com/sehmilo/Customer-Segmentation-in-the-US/blob/main/fed_reserve.ipynb)
Example Data science Project

# Table of Contents
1. [Overview](#Overview)
2. [About](#About)
3. [Data Dictionary](#Data Dictionary)


# Overview
In this project, I used data obtained from the [2019 Survey of Consumer Finances](https://www.federalreserve.gov/econres/scfindex.htm). 

This project is an example of unsupervised learning, specifically **CLUSTERING**. It can be used in commercial contexts for marketing or customer segmentation or in sociological contexts to study social stratification.

Objectives include:
- Compare characteristics across subgroups using a side-by-side bar chart.
- Build a k-means clustering model.
- Conduct feature selection for clustering based on variance.
- Reduce high-dimensional data using principal component analysis (PCA).


# About
The Survey of Consumer Finances (SCF) is normally a triennial cross-sectional survey of U.S. families. The survey data include information on families’ balance sheets, pensions, income, and demographic characteristics. Information is also included from related surveys of pension providers and the earlier such surveys conducted by the Federal Reserve Board. No other study for the country collects comparable information. 
Data from the SCF are widely used, from analysis at the Federal Reserve and other branches of government to scholarly work at the major economic research centers.
The survey has contained a panel element over two periods. 
- Respondents to the 1983 survey were re-interviewed in 1986 and 1989. 
- Respondents to the 2007 survey were re-interviewed in 2009.

The study is sponsored by the Federal Reserve Board in cooperation with the Department of the Treasury. 
Since 1992, data have been collected by the NORC at the University of Chicago.

To ensure the representativeness of the study, respondents are selected randomly using procedures described in the [technical working papers on this web site](https://www.federalreserve.gov/econres/scf_workingpapers.htm). 


A strong attempt is made to select families from all economic strata. Participation in the study is strictly voluntary. 
However, because only about 6,500 families were interviewed in the most recent study, every family selected is very important to the results. To maintain the scientific validity of the study, interviewers are not allowed to substitute respondents for families that do not participate. 
Thus, if a family declines to participate, it means that families like theirs may not be represented clearly in national discussions.

The confidentiality of the information provided in the study is of the highest importance to NORC and the Federal Reserve.
Strenuous efforts are made to protect the privacy of participants, and in the history of the survey, there has never been a leak. 
The names of the participants in the survey are known only to NORC, which has more than 50 years of successful experience in collecting confidential information.

# Data Dictionary*
| ### Feature | ### Description |
| INCCAT | 	Income percentile groups |
| HBUS | 	Have active or non-actively managed business(es) |
| DEBT | Total value of debt held by household, 2019 dollars|
| HOUSES | Total value of primary residence of household, 2019 dollars |
| INCOME | Total amount of income of household, 2019 dollars |
| AGE | Age of reference person | 
| EQUITY | Total value of financial assets held by household that are invested in stock, 2019 dollars |
| FIN | Total value of financial assets held by household, 2019 dollars | 
| KGBUS | Unrealized capital gains or losses on businesses, 2019 dollars |
| ACTBUS | Total value of actively managed business(es), 2019 dollars |
| BUS | Total value of business(es) in which the household has either an active or nonactive interest, 2019 dollars |
| KGTOTAL | Total unrealized capital gains or losses for the household, 2019 dollars |
| NHNFIN | total non-financial assets excluding principal residences, 2019 dollars |
| NFIN | Total value of non-financial assets held by household, 2019 dollars |
| NETWORTH | Total net worth of household, 2019 dollars |
| ASSET | Total value of assets held by household, 2019 dollars |

