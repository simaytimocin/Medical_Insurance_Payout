# Medical Insurance Payout

ACME Insurance Inc. offers affordable health insurance to thousands of customer all over the United States.  In this project, creating an automated system to estimate the annual medical expenditure for new customers, using information such as their age, sex, BMI, children, smoking habits and region of residence.
Estimates from the system will be used to determine the annual insurance premium (amount paid every month) offered to the customer.

Age = Age of the customer

Sex = Gender

BMI = The body mass index (BMI) is a measure that uses your height and weight to work out if your weight is healthy.

Children = Number of children

Smoker = Whether the customer smokes or not

Region = Which region of the country the customer belongs to

Charges = Target variable, the expenditure for the customer

Kaggle link: https://www.kaggle.com/datasets/harshsingh2209/medical-insurance-payout


# REPORT

As a result of my analysis: The medical expenses of smokers are much higher than those of non-smokers. There is a high probability that there is a relationship between smoking and health problems. At the same time, customers with a high BMI have higher health expenditures.

I have observed that using multiple linear regression for this dataset gives much better results than simple linear regression. From the multiple linear regression models, I selected the lasso model as the most suitable model by comparing the MSE values.
