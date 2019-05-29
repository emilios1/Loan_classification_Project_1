# Loan_classification_Project_1.
Loan Classification Project 1.
The purpose of this project is to predict loan defaults. The data was obtained from the Lending Club website. Data cleaning was performed to fill in missing values, drop irrelavent columns, and add columns for analysis using Pandas. The data was explored, visualized, and analyzed using Pandas, Matplotlib, and Seaborn. Machine learning models were built and optimized using Numpy, SciPy, and SK Learn. 

During statistical analysis, the data was grouped by credit grades and it was found that much of the data of different credit grades were distributed differently, with P values of less than 0.0. Due to this, logistic regression models were constructed for each credit grade, along with one logistic regression model containing every loan. The metric that was emphasized is recall because a lender would be interested in knowing the rate of loans from a pool of loans that would be classified correctly.

The logistic regression model containing every loan had a recall of 0.80 in regards to defaults. The logistic regression models segmented by credit grades had recalls of between 0.78 and 0.95 in regards to defaults. Models of higher credit grades achieved higher recall than those of lower credit grades which may be due to inbalance given that lower grades had greater amounts of defaults. However, the differences in the f1 score between fully repaid loans and defaults were not too significant. A random forest model was also built and optimized and achieved a recall of 0.70 in regards to defaults. All models had recalls of 1 in regards to fully repaid loans except for one segmented model that had a recall in respects to fully repaid loans of 0.99.   

This repository also contains neural networks with 98% accuracy.  
