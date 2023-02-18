# Employee-Attrition
Descriptive statistics for numerical and categorical data, 
treating outliers, 
univariate and bivariate analysis, 
heatmap
# Data Description
Attrition Yes: means if the employee departure  from the organization for any reason (voluntary or involuntary), including resignation, termination, death or retirement.
Attrition No: means employee continue with his or her designation in same company hapily.
A daily rate is the billing cost for an individual's services for a single day.
Buissness travel if the employee travels frequently or rarely on company's work. is that the reason to attrit.
Employee distance: how many employees leave far from office, is that the reason for their attrition from company?
Education and education field
if the employee has some relationship issue so it would be the reason for attrition. so realtionship satisfaction rate has been given. rating is from 1 to 4 i.e., not satisfied to satisfied.
stock option level: 0 means not having rights for purchase of company stock and 1: having rigjts on company stock exchange.
Total working years of employee.
Training time last year 0 months or 1, or 2 months
work life balance 0: cant able to balance to able to balance.
how many years at same company.
how many years in same role which they are working.
how many years have been gone since they got their last promotion.
how many years they are working with the same manager.

# Analysis
first we check for missing values. and found that there are no missing values in data.
then next we check for outliers has doubts on 3 features DailyRate, MonthlyIncome, MonthlyRate. so we use bx plot for finding outliers. Montly income has some outliers. so we delete the observations having outliers.
We Observe target variable. we can see that no. of attrition are less than as compare to not get attrition. we can use SMOTE for this type of imbalanced data.
we see univariate analysis for each categorical feature.
see the distribution of Distane from home with attrition. so that we can identify employees resign because they feel difficulty in coming to office.
we drop the columns which we are not needed with like: Over18(all are Over18), Employee number, Emplyee count, Studyhours.
then we find correlation matrix using heatmap.
