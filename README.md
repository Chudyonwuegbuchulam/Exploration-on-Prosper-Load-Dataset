# Exploration-on-Prosper-Load-Dataset
This dataset is a financial one, and its subjects include loans, borrowers, lenders, interest rates, and similar matters. Loans at affordable rates are the company's specialty at San Francisco's Prosper or Prosper Marketplace Inc. The 81 variables associated with each loan in the dataset include interest rate, loan status, borrower income, borrower employment status, borrower credit history, and more. The key objectives of this project are to use summary statistics and data visualisations to depict the features of elements that might affect loan status and to gain some insight into the interactions between various variables.

Preliminary Wrangling

The first step is to import the necessary libraries and packages. In order to load our data and perform fast, vectorized operations on it, we will bring in the Numpy and Pandas libraries, and then the Matplotlib and Seaborn libraries, to enable us create informative visualisations.


Conclusions

The dataset used in this study is comprised of 81 variables and 113,937 observations, all drawn from Prosper loan applications. Due to the large number of potential factors, it will take a considerable time for cleaning. Therefore, I'm only interested in a specific part of the data, so I'm only looking at a subset of the available variables. To understand the data, the dataset was evaluated for insight into its constituent variables using the info and describe functions. Afterwards, the BorrowerAPR became the primary emphasis of the probe.

Some columns were eliminated during data wrangling since they contained information that would not contribute to the analysis. All fields were inspected for null values, and columns with more than 50% blanks were eliminated.

The annual percentage rate (APR) charged to borrowers is inversely proportional to the amount of principal repaid each month. ProsperRating is negatively correlated with BorrowerAPR. An individual's ProsperRating affects their annual percentage rate (APR). In general, the lower the BorrowerAPR, the higher the Prosper Rating. It was also found that the BorrowerAPR decreases for very long loan terms. The BorrowerAPR also has a weak inverse relationship with whether or not the borrower is currently employed. This means that the BorrowerAPR is lower for those who are employed, self-employed, or work part-time than it is for those who are jobless, retired, or in a different category. The data shows that across all income brackets, 12-month loan periods are more popular than shorter ones. For those with an annual salary of above $100,000, the highest monthly payment option is also the longest repayment term.


Limitation

The amount of missing information in our data set was quite large. Once we eliminated the blanks from the data, we were left with around 75% of the original data. This is still a respectable sample size, but it raises questions about how widely we can extrapolate the results of our investigation. Since the focus of this research has been on investigating possible associations between factors, it is not possible to state with any degree of certainty that any given factor is responsible for any given outcome. A mere observational research was conducted. A carefully designed experiment is necessary to prove a causal connection.
