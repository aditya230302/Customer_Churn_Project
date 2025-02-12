# Customer_Churn_Project

Problem Statement:
You are the data scientist at a telecom company named “Neo” whose customers are churning out to its competitors. You have to analyze the data of your company and find insights and stop your customers from churning out to other telecom companies.

Environment: Jupyter Notebook 

Domain: Telecom & Data Analysis

Tasks To Be Performed:

1. Data Manipulation:
- Extract the 5th column and store it in ‘customer_5’
- Extract the 15th column and store it in ‘customer_15’
- Extract all the male senior citizens whose payment method is electronic check and store the result in ‘senior_male_electronic’
- Extract all those customers whose tenure is greater than 70 months or their monthly charges is more than $100 and store the result in ‘customer_total_tenure’
- Extract all the customers whose contract is of two years, payment method is mailed check and the value of churn is ‘Yes’ and store the result in ‘two_mail_yes’
- Extract 333 random records from the customer_churndataframe and store the result in ‘customer_333’
- Get the count of different levels from the ‘Churn’ column

3. Data Visualization:
- Build a bar-plot for the ’InternetService’ column:
  - Set x-axis label to ‘Categories of Internet Service’
  - Set y-axis label to ‘Count of Categories’
  - Set the title of plot to be ‘Distribution of Internet Service’
  - Set the color of the bars to be ‘orange’
  - 
![{CBD45F15-3C86-4DD7-A00D-627DA787C4B3}](https://github.com/user-attachments/assets/d1850632-114b-4ede-850f-cfb7ba861491)

- Build a histogram for the ‘tenure’ column:
  - Set the number of bins to be 30
  - Set the color of the bins to be ‘green’
  - Assign the title ‘Distribution of tenure’
  - 
![image](https://github.com/user-attachments/assets/2f394186-efc3-4f36-8650-b5c474df1b60)

- Build a scatter-plot between ‘MonthlyCharges’ and ‘tenure’. Map ‘MonthlyCharges’ to the y-axis and ‘tenure’ to the ‘x-axis’:
  - Assign the points a color of ‘brown’
  - Set the x-axis label to ‘Tenure of customer’
  - Set the y-axis label to ‘Monthly Charges of customer’
  - Set the title to ‘Tenure vs Monthly Charges’
  - Build a box-plot between ‘tenure’ & ‘Contract’. Map ‘tenure’ on the y-axis & ‘Contract’ on the x-axis.
  - 
![{B77BE565-BE12-4A96-801B-4063B1437E2D}](https://github.com/user-attachments/assets/ac980e40-ffd9-4b64-8917-f0d9c2fe30cf)

![{CB8BD16D-7596-4FFB-B4B9-6B2E5BD5CA70}](https://github.com/user-attachments/assets/f1bd2b17-09e3-45e8-b26a-81611af3ac0f)

- Insights:
  - Longer contracts lead to higher customer retention.
  - Month-to-month contracts have a high churn risk, as many customers leave early.
  - Customers with two-year contracts are the most committed, staying significantly longer on average.

4. Linear Regression:
- Build a simple linear model where dependent variable is ‘MonthlyCharges’ and independent variable is ‘tenure’:
  - Divide the dataset into train and test sets in 70:30 ratio.
  - Build the model on train set and predict the values on test set
  - After predicting the values, find the root mean square error
  - Find out the error in prediction & store the result in ‘error’
  - Find the root mean square error

5. Logistic Regression:
- Build a simple logistic regression model where dependent variable is ‘Churn’ and independent variable is ‘MonthlyCharges’:
  - Divide the dataset in 65:35 ratio
  - Build the model on train set and predict the values on test set
  - Build the confusion matrix and get the accuracy score
  - Build a multiple logistic regression model where dependent variable is ‘Churn’ and independent variables are ‘tenure’ and ‘MonthlyCharges’
  - Divide the dataset in 80:20 ratio
  - Build the model on train set and predict the values on test set
  - Build the confusion matrix and get the accuracy score

6. Decision Tree:
- Build a decision tree model where dependent variable is ‘Churn’ and independent variable is ‘tenure’:
  - Divide the dataset in 80:20 ratio
  - Build the model on train set and predict the values on test set
  - Build the confusion matrix and calculate the accuracy

7. Random Forest:
- Build a Random Forest model where dependent variable is ‘Churn’ and independent variables are ‘tenure’ and ‘MonthlyCharges’:
  - Divide the dataset in 70:30 ratio
  - Build the model on train set and predict the values on test set
  - Build the confusion matrix and calculate the accuracy
