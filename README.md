# IBMH-Hr-Analysis

1. I am predicting workers attrition based on the data. My response variable will be Attrition

2.  There are 1470 observations dataset

3. 16% of them have “yes” in attrition, 84% of them have “no”

4. First I did in this project was to add the new columns for the categorical variables, you can see these changes on the sheet called “Added Columns”

5. Also, I found min, max, range, mean, median, a mode for each column

6. I normalized data, and you can see this in the sheet called “Normalize” the only values now I have is between 0 and 1

7. I randomized my data and took the first 80% for my training set and 20% for my test set

8. In the training set, you will see the steps which I did. After running the solver Sum Squared Error is less and Total Sum of Squares and R squared is positive which shows the variation of 27% in my response variable. I also calculated F statistic and P value

9. Next sheet is called “ModelCoefficientSTDError” in which I did the calculations to get the numbers for Coefficients STD Error, t statistics, and t-test-p-value

10. In my test set, I did the same calculations but without the solver, and got r-squared 16%

11. In my “performance” sheet I have my ROC curve

12. Based on the data I can say that if people want to stay in the company, education is very important, also activities such as traveling and participation. People need to have a high-performance rating and relationship satisfaction.
