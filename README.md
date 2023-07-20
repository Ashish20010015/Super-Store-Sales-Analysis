## Super-Stotre-Sales-Analysis
I am using the dataset from https://github.com/Ashishbeaprogrammer/Super-Stotre-Sales-Analysis/blob/main/SuperStore_Sales_Dataset.csv
Each row of the dataset contains information about an order. The following order details are available:
1.'Row ID'
2.'Order ID'
3.'Order Date'
4.'Ship Date'
5.'Ship Mode'
6.'Customer ID'
7.'Customer Name'
8.'Segment'
9.'Country'
10.'State'
11.'Region'
12.'Product Id'
13.'Category'
14.'Sub-Category'
15.'Product Name'
16.'Sales'
17.'Quantity'
18.'Profit'
19.'Returns'
20.'Payment Mode'
21.'ind1'
22.'ind2'

There are 5902 rows and 22 columnsare present in the dataset.

## Technolohies Used:
For importing, manipulating, and exploring data, I utilised Pandas; for data visualisation, I used Seaborn and Matplotlib. Additionally, I created the analytical dashboard using PowerBI.

## Data Exploration
1. Checked For missing Values.
All the columns have data for every row except for Returns,ind1,ind2 columns which have missing data points.

2. Delete the columns which are not required for analysis.
Row ID,Order ID, Product ID, Customer ID,Product Naame, Customer Name are not required for Analysis process.

3. Find the Categorial Value.
I have considering the features with less than 50 unique values as categorial data.These are the categorical features in the dataset 'State', 'City', 'Ship Mode','Region', 'Segment', 'Category', 'Sub-Category', 'Payment Mode'.

4. For each categorical data, I explored the distribution of their values using pie chart and Bar Chart. Following insights were gained:  
a. Most of the order are from **West** region.
b. Majority of the customers are **Office supplies** and **Technology** are the most sold product category.
c. **Blienders** and **Papers** are the most popular Sales product.
d. Most popular shipping mode is **Standard Class** with 58% of the orders being shipped by this mode of transport.
e. Most popular payment mode is **COD** with 43% of the order.

5. The data is available for 2 years 2019 - 2020. 
a. 2020 is the most profitable year and 2019 as the least profitable.
b.I made bar graph for sales, Quantity. There was no significant change in over the years which could indicate a drop in profit for 2019.

## Data Visualization using PowerBi
1.Following isnsights were gained:
a. Most of the order are from **West** region.
b. Majority of the customers are **Office supplies** and **Technology** are the most sold product category.
c. In comparison to other months, the profit rate is greater in the month of **December**.
d. Most popular shipping mode is **Standard Class** with sales 0.33M.





