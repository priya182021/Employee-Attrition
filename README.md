#**employee Attrition**
Attrition Yes: indicates that the employee left the organisation for whatever cause (voluntary or involuntary), such as resignation, termination, death, or retirement.
Attrition No: signifies that the employee is happy with his or her position in the same organisation. A daily fee is the cost of a single day's services for an individual. 
Business travel occurs when an employee travels frequently or seldom for corporate business. Is this the reason for attrition?
Employee distance: how many employees leave far from the workplace, and is this the reason for their business attrition?
Education and education area would be the reason for attrition if the employee has certain connection issues. 
As a result, a relationship satisfaction rating has been assigned. Ratings range from 1 to 4, indicating dissatisfaction to satisfaction. 
Stock option level: 0 signifies no rights to acquire business stock, and 1 means rights to trade firm stock on the stock exchange.
Employee's total number of working years. 
Last year's training time was 0 months, 1 month, or 2 months. 
Work life Balance,0: from being unable to balance to being able to balance.
How long have you been with the same company? 
how many years have they worked in the same position? 
How many years have passed since their previous promotion? 
how long they have been working with the same management.

**Analysis**
We begin by looking for missing values. and discovered that the data has no missing values.
Next we look for outliers that have questions about three attributes. MonthlyIncome, MonthlyRate, DailyRate. As a result, we employ the bx plot to identify outliers. Outliers in monthly income exist. As a result, we discard the observations that contain outliers.
We observe the variable of interest. We can observe that the number of attrition is lower as compared to not having attrition. SMOTE can be used to handle this sort of unbalanced data. 
For each category characteristic, we show univariate analysis. 
See the attrition distribution of Distane from home. so that we can identify individuals who resign because they find it difficult to come to work. 
We remove the columns that are no longer required, such as Over18 (all are Over18), Employee number, Employee count, and Studyhours. 
The correlation matrix is then discovered using a heatmap.
