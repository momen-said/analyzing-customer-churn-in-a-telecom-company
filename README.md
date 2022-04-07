# Analyzing Customer Churn in a Telecom Company

## Background:
For subscription-based businesses, reducing customer churn is a top priority, In this case study, I'll investigate a dataset from a telecom company called Databel and analyze their churn rates. Analyzing churn doesn’t just mean knowing what the churn rate is: it’s also about figuring out why customers are churning at the rate they are, and how to reduce churn. 

## Data Preparation:
first, the data was obtained from https://app.datacamp.com/ which is an excel sheet.

then i started to prepare the data for the analysis process by cleaning it and discovering it on excel pivot table.

## Data Processing:
for processing, i uploaded the data on Tableau Public, where i calculated some measures for the analysis process, then created the workbooks and combining them in one dashboard.

in the analysis process, i calculated some measures, like:
- churn rate = ([number of churned customers]/ COUNT([Customer ID]))*100
- number of churned customers = count(if [Churn Customers - Binary] = 1 then [Customer ID] end)
- total number of customers = COUNT([Customer ID])

here is the dashboard after i have finished it:

![tableau dashboard 1](https://user-images.githubusercontent.com/79236835/162142275-2e8a0043-eacc-45c4-bff5-9a3b2dc40a55.png)


what I have noticed that California state has the highest churn rate (63%) compared to the number of customers, and most of them are leaving the company because the competitor had better offer or devices, also most of the leaving customers are the month-to-month subscription customers
also Oklahoma has the least churn rate (19%), which is because of the competitor also.
also most of the leaving customers are leaving mainly because the competitor has better offers or devices, but many also leave because of the attitude of the employees, or dissatisfaction (which is an indirect reason also for the competitor to acquire new customers)
also most of the leaving customers are at age between 27 and 55 for men, and between 25 and 47 for women
the overall churn rate ns 26% which is high unfortunately.
also most of the leaving customers are the "month-to-month subscription" customers.


https://user-images.githubusercontent.com/79236835/162142019-6e6ee589-30d4-4f77-aa5a-44b5b2bace25.mp4


# in conclusion, we can say that the churn rate is high nearly in all the states, which must be faced with a great effort to minimize it by solving the main problems faced by the customers and by making marketing campaings to compete with the other companies .

And finally, you can check the dashboard from here: https://public.tableau.com/app/profile/mo.men.said/viz/analysingchurnintelecomcompany/Dashboard1

