# Superstore Data Analysis

The analysis of the Superstore dataset was aimed at discovering relationships between the features in the dataset and gaining meaningful insights from the relationships.

The analysis was carried out using Python and the visualizations were created using panda, Matplotlib and Seaborn.



## Installation 

``` 
import numpy as np 

import pandas as pd 

import matplotlib.pyplot as plt 

import seaborn as sb 

sb.set_style("darkgrid") 

%matplotlib inline 
```



## Dataset

The Superstore dataset contains transaction data 
for purchases made by customers residing in the US. 
Sales at the Superstore were generally targeted towards consumers, 
customers shopping for home office, and customers shopping 
for corporate use. Besides the segment, 
other features contained in the dataset include 
shipping mode, country, city, state, and region 
where the customer resides, postal code, category, 
subcategory, sale price and quantity of the product 
purchased by the customer, the profit gained, 
and the discount given on the product. 
A total of 9,994 entries were made on these features. 
The dataset can be found [here](https://www.kaggle.com/datasets/ibrahimelsayed182/superstore/download?datasetVersionNumber=1) 



## Summary of Findings

Exploratory analysis of the superstore dataset showed that: 

- Most customers opt for standard class for shipping their purchases.

- A few customers use second class and first class, 
but only approximately 5% of customers opt for same-day shipping. 

- The vast majority of products are purchased by consumers.  

- The majority of customers reside in the West, 
followed by the East, 
then Central and Southern US.

- Purchases are mostly made by customers 
residing in California, with the city of 
Burbank producing the most profit. 

- Office supplies are by far the most purchased category of products, 
with binders and paper being in the highest demand.

- Products sold at low prices are the most purchased, 
causing profit yield to be mostly within the range of 
\\$0-50. Also, products are mostly bought in quantities of 2 and 3, 
and product purchases in quantities of 10-12 are rare.

- Technological products generate the most profit.

- While profit increases with an increase 
in the number of products purchased, the type of product 
purchased also greatly influences the degree of increase in the profit.

- In the Central, East, South, and West regions of the United States, 
the highest profits are produced by Texas, New York, 
Virginia, and California respectively.

- California and New York generate the highest 
amongst these high-profit producing states in each region.

- Most products purchased for home offices have a low sale price, 
and consequently low profit. 
Products purchased by consumers are generally higher in sale price 
and yield higher profits. 
