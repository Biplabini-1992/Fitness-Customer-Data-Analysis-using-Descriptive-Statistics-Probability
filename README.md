# Fitness Customer Data Analysis using Descriptive Statistics & Probability
### Business Problem:
The market research team at AeroFit wants to identify the characteristics of the target audience for each type of treadmill offered by the company, to provide a better recommendation of the treadmills to the new customers. The team decides to investigate whether there are differences across the product with respect to customer characteristics.

1. Perform descriptive analytics to create a customer profile for each AeroFit treadmill product by developing appropriate tables and charts.
2. For each AeroFit treadmill product, construct two-way contingency tables and compute all conditional and marginal probabilities along with their insights/impact on the business.

## Dataset Information:
Aerofit is a leading brand in the field of fitness equipment. Aerofit provides a product range including machines such as treadmills, exercise bikes, gym equipment, and fitness accessories to cater to the needs of all categories of people.
The company collected the data on individuals who purchased a treadmill from the AeroFit stores during the prior three months.
### Source:
Please check the dataset at: https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/125/original/aerofit_treadmill.csv?1639992749

### Feature Information:
Product: Product Purchased KP281, KP481, or KP781 

Age: In years 

Gender: Male/Female 

Education: in years 

MaritalStatus: single or partnered 

Usage: average number of times the customer plans to use the treadmill each week 

Income: annual income (in $) 

Fitness: self-rated fitness on a 1-to-5 scale, where 1 is the poor shape and 5 is the excellent shape 

Miles: average number of miles the customer expects to walk/run each week

### Product Portfolio:
1. The KP281 is an entry-level treadmill that sells for 1,500.
2. The KP481 is for mid-level runners that sell for 1,750.
3. The KP781 treadmill has advanced features that sell for $2,500.

## Key-Highlights:
#### Data Structure and Characteristics:
1. Overview of the dataset's structure, including the number of rows and columns.
2. Data types of each column.
3. Descriptive statistics like mean, median, standard deviation, etc.
   
#### Outlier Detection:
1. Identification of outliers using boxplots and the difference between mean and median for numerical variables.
   
#### Effect of Demographic Features on Product Purchased:
1. Analysis of how features like marital status, age, gender, etc., affect the product purchased.
2. Visualization using countplots, histograms, boxplots, etc.
   
#### Marginal Probability of Product Purchases:
1. Calculation of marginal probabilities for products like KP281, KP481, and KP781 using pandas.crosstab.
2. Representation of marginal probabilities in a table format.
   
#### Correlation Analysis:
1. Exploration of correlations among different factors using heat maps or pair plots.
2. Identifying relationships between variables that may influence product purchases.
   
#### Probability Calculation:
1. Calculation of the probability of a male customer buying a KP781 treadmill.
2. Interpretation of the probability in the context of customer behavior.
   
#### Customer Profiling:
1. Categorization of users based on their characteristics, behaviors, and product preferences.
2. Understanding the different segments within the customer base.

#### Recommendations:
1. Providing recommendations based on the insights gained from the analysis.
