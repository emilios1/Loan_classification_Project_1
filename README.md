# Loan_classification_Project_1.
Loan Classification Project 1.
This project was done with the intention of predicting defaults. The data was obtainted from the Lending Club website. 
Data wrangling was performed to fill in missing data, drop irrelavent columns, and create new columns. The dataset was 
made into a data frame containing over 45000 observations and 23 columns. The data was then explored and analyzed. It was 
decided to build logisitic regression and random forest models. One logisitc regression model contained every loan. Other 
logistic regression models contained a single credit grade type each. Grades are credit scores ranked in grade letters. The 
logistic regression models classified every fully paid loan in the data as such, and more than 80% of the defaults, in some 
cases over 90% of the defaults. The random forest model correctly classified every fully paid loan and 62% of the defaults. The
validation metric mostly emphasized is the recall rate. 
