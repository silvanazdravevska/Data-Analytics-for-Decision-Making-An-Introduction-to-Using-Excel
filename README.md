## Data-Analytics-for-Decision-Making-An-Introduction-to-Using-Excel

futurelearn.com

### Course: Data Analytics for Decision Making: An Introduction to Using Excel

Introductory course for those with interest in data analytics or data science and how it can be used to improve business decision making

### Institution: Bond University

### Case Study: Analyzing historical sales of Supermarket Company recorded in 3 different branches for First Q3 in 2019

### Level: Introductory

### Date of completion: 2020-07-02

## Analyzing historical sales of Supermarket Company recorded in 3 different branches for First Q3 in 2019

### Data:

AUNG PYAE (2019). Supermarket sales [Dataset]. https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales 

The dataset is one of the historical sales of Supermarket Company which has recorded in 3 different branches for 3 months data.

### File descriptions:

•	supermarket_sales.xlsx - Daily sales data covering 3 months.

### Column descriptions

•	Invoice id: Computer generated sales slip invoice identification number

•	Branch: Branch of supercenter (3 branches are available identified by A, B and C)

•	City: Location of supercenters

•	Customer type: Type of customers, recorded by Members for customers using member card and Normal for without member card

•	Gender: Gender type of customer

•	Product line: General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel

•	Unit price: Price of each product in $

•	Quantity: Number of products purchased by customer

•	Tax: 5% tax fee for customer buying

•	Total: Total price including tax

•	Date: Date of purchase (Record available from January 2019 to March 2019)

•	Time: Purchase time (10am to 9pm)

•	Payment: Payment used by customer for purchase (3 methods are available – Cash, Credit card and E-wallet)

•	COGS: Cost of goods sold

•	Gross margin percentage: Gross margin percentage

•	Gross income: Gross income

•	Rating: Customer stratification rating on their overall shopping experience (On a scale of 1 to 10)

### Graphical Descriptive Techniques
#### Pie Chart & Bar Chart
Appropriate when data can be naturally categorized in a meaningful manner. I chose the columns Payment and Tax 5% to inspect via these Charts. For that purpose I copied the Payment and Tax 5% columns in the Sheet Pie & Bar. Then, I consolidated the data by payment type and inserted a Pie and a Bar chart. The data labels displayed on the Pie chart are in percentage, and the ones on the Bar chart are the accumulated values of the tax for each payment type.

Pie chart - Tax 5% on type of payment during the first trimester of 2019 in percentage

Bar chart - Accumulated Tax 5% on type of payment during the first trimester of 2019

Conclusion: Accumulated Tax 5% on type of payment during the first trimester of 2019 was almost the same for the three payment methods, meaning all payment methods are almost equally used among buyers.

#### Histograms
I chose column Total, which is total price including tax. I used Histograms from Data Analysis, not from charts. Summarize by categories (bins): 0-100, 100-500, 500-1000, 1000-1500.

Conclusion: Most frequent is total from 500-1,000 total price. If we need to further analyze the Product Line, I would use Consolidate, where I can discover the differences or similarities between the total prices.

#### Line Pots & Satter Plots
Graphing Time Series

Line plots are valuable tools for visualizing how a variable changes across time

Scatter plots are similar in that they visualize two variables at once that might be related to one another. Columns used: Date and Rating.

Conclusion: There is no relationship between the date of shopping and the gross income for the same time period. Further analysis can provide insight if shopping trends during weekend are more frequent then weekdays.

### Descriptive Statistics for Summarizing Data
#### Measures of Central Location
They all describe the center of the data

Mean - tells us the average value

Median - tells us the middle. Median arrange values in order.

Mode - tell us the most frequent. 

#### Measures of Variability
How spread out are the data around the central location

Range – Largest minus Smallest measurement 

Variance and Standard Deviation – Cogs have a high variance, which indicates the data points are very spread out from the mean, and from one another, and in contrast, in Rating, the data points are closer to the mean, and to each other.

For comparison, the Variance and Standard deviation of the population are calculated with formulas, as sample values are calculated through Data Analysis.

#### Measure of Shape
Skewness – For cogs > 0, meaning skewness is right (positive), for Ratings = 0, meaning it’s symmetric

For comparison, the skewness of the population is calculated with formulas, as sample values are calculated through Data Analysis.

For better visual representation, I created histograms on both attributes. The Mean of each I represented with a manually added orange line, and the Median is represented with a purple line. Where those lines intercept, it means skewness is symmetric (Rating). And if the mean is drawn towards the extreme values, it means skewness is right (cogs).

#### Measures of Association
Measure of correlation is useful for determining whether there is a linear relationship between two variables. It is very important to remember that a strong correlation does not mean that one variable causes the other.

Coefficient of correlation of attributes Unit price and Quantity = 0, meaning there is no Correlation between the two attributes and are linearly unrelated. For better visualization I added a Scatter plot to observe the correlation.

### Probability
Attributes chosen are City and Customer type

#### Assigning Probabilities
Empirical approach, based on relative frequency – Example: Probability of selecting Yangoon customer type from all cities and all customer types

Classical (a priori) approach, based on prior knowledge of process – Example: Probability that Mandalay members will undertake shopping

Event Relations - Value of probabilities are randomly assigned, with no previous calculations. The formula used to calculate probability:
P(Members rise &cup; Normal rise) = P(Members rise) + P(Normal rise) – P(Members rise &cap; Normal rise)

#### Discrete Random Variables
Calculating probability of profit by Product Line. I got the probability by dividing the total profit per product line and the sum of total profit of all product lines. To calculate the mean Total Profit and Probability were multiplied. 

Expected Value of Total profit = 53917,61 with a Standard Deviation = 2136,533925.

A lower Standard deviation, the smaller the spread, means a lower risk. To summarize, the preference is a higher expected cash flows and lower variance. 

Measure of risk per unit of expected profit is Coefficient of variation =  0,039625899. Again, the lower the value, the lower the risk. 


