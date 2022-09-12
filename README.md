NB: This is a template to make documentation process easy. You can remove the `To-Do` notes in your final commit

# Project Title: Trend Analysis of Company XYZ sales

## Description:

#### A deep dive into the analysis of the sales data of company XYZ to identify trends, patterns and other useful insights. Furthermore to determine measures to drive more sales and increase growth

# Project Steps

#### IMPORTING LIBRARIES AND LOADING DATASETS FOR ANALYSIS
- Import my libraries
- forked my project on github
- then used the git bash command prompt to clone the project to my personal computer and then open the jupyter notebook file
- loaded my datasets using the glob function
- combined all the dataset using the concat() method.

#### DATA EXPLORATION
- used the df.head() to get the first few rows of the data set to get a glimpse of my data set
- looked at the number of rows and column in the dataset using the df.shape()
- generated the columns of the dataset to know if my columns are properly formated using df.column attribute
- changed the column case to lower case using the str.lower() method
_ took the statistical summary of the numerical columns in the dataset
- took the liberty of putting out insights I could find from the statistical summary
- checked for missing values in the data set but there was no missing values
- also checked the data types in the all the columns using the df.info() method

#### DEALING WITH DATE AND TIME

- converted the datetime columns formated in object datatype to datatime datatype using the  to_datetime() method.
- also extracted the day, month, time data from the date and time columns and made new columns with them and used the df.head() method to view the changes made to the data set.

#### UNIQUE VALUES IN COLUMNS
- iterate through the columns and check if each element is an object datatype. The result is saved to the "categorical_columns" variable as a list
- determined the unique values in each of the categorical column in the data set and printing it to the terminal

#### AGGREGATION AND ANALYSIS
- grouped the dataset by city column and aggregated it with the sum and mean column
- Used the groupby object, display a table that shows the gross income of each city, and determine the city with the highest total gross income with the max() method
- I also selected the quantity and unit price column, aggregated with the sum function and passed into a dataframe 

#### DATA VISUALIZATION
- Used countplot() to determine the branch with the highest sales record.
- Extended it to determine the most used payment method and city with the most sales.
- Determined the highest & lowest sold product line, using Countplot
- Determined the Payment channel used by most customer to pay for each product line using the countplot
- Determined the Payment channel for each branch
- Determined the branch with the lowest rating using boxplot. I also grouped the dataset by branch to determine the branch with the lowest rating
- I also plotted other viz for useful insights

# Insights

- The branch with the most sales is A
- The highest payment method is Epay
- The city with most sales is the Lagos City
- The highest product line is Fashion Accessories
- The lowest product line Health and Beauty
- Food and Beverages uses Card payment the most
- Fashion accessories uses Epay payment method - more
- Electronic accessories uses Cash payment method more
- Sports and travel uses Cash payment method more
- Home and Lifestyle uses Epay payment method more
- Health and beauty uses Epay payment method more
- Branch A uses Epay more but also use card and cash
- Branch B uses card more but also use epay and cash
- Branch C uses Cash more but also use epay and card
- All three Branches have the same minimum value of 4.0
- Electronic accessories recorded the lowest unit prices
- fashion accessories have the highest unit price
- Fashion accessories has the lowest quantity sold one of the reasons would the price per unit compared to other product in the product line
- Electronic accessories sold more in quantity than other product line
- This viz tells us that there are more male customers in Abuja and Lagos city hence emphasis should be made on goods predominantly consumed by males.
-From the viz above, it is deduced that female customers purchase more Fashion accessories from the product line
- From the viz, I discovered that there were more customers who purchased health and beauty products than female
- Also, female bought more sports and travel products
- The line plot shows a trend nominal value change which indicates that company xyz has recorded continuous income range and quantity of goods sold which indicates little or norminal growth rate for the period the data was collected

# Future Work

In the future I will include regression analysis to generate insights between quantity, gross income and cost of goods sold. I will also like to analyze rating data and the customer type to get more insights on how to retain more customers

# Standout Section

Following the instructions in the notebook, what I did differently was converting all the column formatted strings to lower case for easy reference purposes and I added some visualization to my analysis.

Another step I took individually is introducing the git bach command prompt to track the versions of my work, clone the repository, and also commit the changes back to github repository. 

I aslo did have to change the working directory and path name for me to effectively use the glob command.
# Executive Summary.

To-Do - Include your Executive Summary document in your repository.
