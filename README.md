# HR-analytics-Attrition
Goal: To find the factors which affect the attrition rate and company has to concentrate on which factor and predict the attrition of employees and try to reduce it.
Tool use : Power BI

This is my First Power BI Dashboard Which i created during my internship training program.The dataset i used HR Analytics Employee Attrition from Kaggle . This is the Business Problem of IBM company about Predict attrition of their valuable employees.

🔖Data Source : https://lnkd.in/dUS3RsgJ

🔖Business Problem:
To find the factors which affect the attrition rate and on which factor we have to concentrate so we can able to predict the attrition of employees and try to reduce it.

🔖 Benefits:
✨ If they get the insights from the data then they can easily identify which factor impact more which they have to focus on.
✨ Also Company can make strategies regarding how they will reduce the attrition of employees.

🔖 About the Dashboard :
The dashboard provides the Attrition Count/No. and percentage of employees on basis of different factors.
1. Create HR analytics Dashboard in which it show Attrition count and percentage by donut chart, Create measure for Attrition %, Some filters also use and different charts are using.
2. The analysis of Attrition Rate is done on various factors to give the proper insights for the company to take decision.

✅Created the following Dim Table -
✨ Education.
✨ Job Level
✨ Job Involvement
✨ Job Satisfaction
✨ Performance Rating
✨ Relationship Satisfaction
✨ Work Life Balance
and having one Fact Table-
HR Employee Attrition

✅Create Measures(to calculate Attrition%) using DAX query-

✨To find the no. of employees who have 'Yes' for the attrition -
CountofYes= COUNTROWS(FILTER('fact-HR Employee Attrition','fact-HR Employee Attrition'[Attrition]="Yes"))

✨To find the No. of total observations-
Totalobs= COUNTROWS('fact-HR Employee Attrition')

✨ Atlast find Attrition % by dividing "CountofYes" measure by "Totalobs" measure
Attrition % = [CountofYes]/[Totalobs]*100

🔖Points From Insights:
1. Employees that studied in Marketing and technical had a higher attrition rate than all other.
2. Attrition was slightly higher for males.
3. Singles were more likely to leave the company than divorced and married employees.
4. Employees thar are not satisfied in company and did not have a healthy worklife balance were more likely to leave.
5. Training also is imp. factor , the employees that recieved no training have slighty have high chance of Attrition rate.
6. Employees that were not involved in their work tended to leave
7. Employees were more likely to leave when they did overtime.
8. Employees that travelled frequently were more likley to leave.

🔖Key Takeaways:
1. Learned about telling data-driven story with this dashboard.
2. Understand the factors which affects more in attrition rate.
3. Get knowledge of creating measures from DAX.
4. Developed Analytical and critical thinking.
5.Developing to know what type of charts are choose for showing particulars problem.
6. Learn to do ehnance the dashboard by doing formattings.
