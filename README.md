Aerofit is a leading brand in the field of fitness equipment. Aerofit provides a product range including machines such as treadmills, exercise bikes, gym equipment, and fitness accessories to cater to the needs of all categories of people.

Business Problem 

The market research team at AeroFit wants to identify the characteristics of the target audience for each type of treadmill offered by the company, to provide a better recommendation of the treadmills to the new customers. The team decides to investigate whether there are differences across the product with respect to customer characteristics. Perform descriptive analytics to create a customer profile for each AeroFit treadmill product by developing appropriate tables and charts. For each AeroFit treadmill product, construct two-way contingency tables and compute all conditional and marginal probabilities along with their insights/impact on the business.

About 

The company collected the data on individuals who purchased a treadmill from the AeroFit stores during the prior three months. The dataset has the following features:

Product Purchased: KP281, KP481, or KP781

Age: In years

Gender: Male/Female

Education: In years

MaritalStatus: Single or partnered

Usage: The average number of times the customer plans to use the treadmill each week.

Income: Annual income (in $)

Fitness: Self-rated fitness on a 1-to-5 scale, where 1 is the poor shape and 5 is the excellent shape.

Miles: The average number of miles the customer expects to walk/run each week


Approach Used

For this project,  I have tried to predict the customer behaviour regarding 3 types of treadmills that are KP281, KP481 and KP781. What is the gender, marital status, age, education, miles, fitness, income and usage distribution for each product.I have done EDA like finding the data type of the columns, finding the shape of the dataset, found the number of missing values in each column, made use of boxplots to detect the outliers and also used np.clip() for clipping the data. I utilized countplots, histplots, pie charts and boxplots for data visualization. To assess correlation, I employed Heatmap. Also created Contingeny tables to predict the conditional and marginal probabilities so that, it would provide better insights to predict the purcahse pattern of the different customers.
