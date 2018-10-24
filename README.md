# Overview:

To forecast sales for walmart product categories in their store based on the sales history of each category.

Forecasting of retail sales helps retailer to take necessary measures to plan their budgets or investments in a period (monthly, yearly)
among different product categories like women clothing, men clothing and other clothing and at the same time they can plan to minimize 
revenue loss from unavailability of products by investing accordingly.

# Evaluation:

The evaluation metric for this competition is RMSE

# Datasets:

1. Macro Economic Dataset 2. Events and Holidays Dataset 3. Weather Data Set 4. Train Data (Sales and the Year/Month) 

Python Program to predict sales for the leading retailer WALMART using Regression techniques such as Linear Regression, KNN, Decision Tree
Regressor and tried boosting the algorithm with Gradient Boosting.

# Exploratory Data Analysis:

   - Plotted Heat Map to find the correlations between the independent variables 
   - Plotted the Box Plot to find the distribution pattern for each independent variable and also to find the outliers
   
# Missing Value Handling:
   - Advertising Expenses column has lot of missing values, but if we could see in the business perspective may be we might have not 
     contributed for Advertisement during that particular month. So instead of dropping it, I have replaced the missing values with zeroes 
     indicating no contribution towards the advertisement.
   - Target column (SALES) also had missing values ( 12 Values are missing) since the count is less i have replaced them with the 
     Median values
      
# Outliers Treatment:
   - Cotton Monthly Price and it % change have huge number of outliers - Treated the outliers
     Treatment : Get the median and the standard deviation of every group and Subtract median from every member of each group. Take
     absolute values > 3 standard Deviation and have replaced them with the median of those outliers.
     
