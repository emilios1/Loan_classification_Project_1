# Loan_classification_Project_1.
Loan Classification Project 1.
This project was done with the intention of predicting defaults. The data was obtained from the Lending Club website. 
Data wrangling was performed to fill in missing data, drop irrelevant columns, and create new columns. The dataset was 
made into a data frame containing over 45000 observations and 23 columns. The data was then explored and analyzed. It was 
decided to build logistic regression and random forest models for classification. One logistic regression model contained every loan. Logistic regression models were also made for each credit grade. Grades are credit scores ranked in grade letters. A single random forest model containing every loan was built. The 
logistic regression models classified every fully paid loan in the test set as such, and more than 80% of the defaults, in some 
cases over 90% of the defaults. The random forest model correctly classified every fully paid loan and 62% of the defaults in the test set. The
validation metric mostly emphasized is the recall rate. 
