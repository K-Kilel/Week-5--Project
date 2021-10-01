
**TEAM: SLYTHERIN**

**Team Leader**

Kelvin Kilel

**Team Members**

Brenda Koro

Joseph Kiburu

Edward Sang

Rose Onyango

Kelvin Kilel

**Business Understanding**

Retailing involves the process of selling merchandise and certain services to customers through multiple supply chains to make a profit. People have been sharing, selling bartering and consuming resources for nearly as long as people have existed. This form of trading has evolved over the years especially after the industrial revolution when retailing really took off. Currently, retail is one of the most important aspects in the chain distribution channel. The most common examples of retailing include globally recognized stores such as Big Mart, Walmart, Target and Best Buy. Retailing also includes small kiosks at a local mall. 
Big Mart is an international well known brand which has stocks of expansive items, from groceries and soft drinks to tobacco products, magazines and newspapers. With more than 40 outlets in the world, Big Mart is taking over the retail industry. In time, Big Mart will be the most preferred convenience store,  taking into account their excellent customer service and high quality products. Big Mart aims at improving their products and customer service even further, considering the manner in which they highly prioritize customer satisfaction.

**Problem statement**

All retail businesses strive to get analytical data on inventory levels, supply chain movement, consumer demand, sales among others that are crucial for making marketing, and procurement decisions. Big Mart, not exceptional, has 1559 products in 10 stores as of 2013 data that need to be critically analyzed to get some insights to aid better decision making.

**Main Objective**

To understand the attributes of products in Big Mart and the attributes of Big Mart outlets which create important insights for decision making.

**Specific Objective**

The most sold product? What was the total sales?

Which type of  fat content product has the most sales? What was the total sales?

The most visible product? Is it the most selling product?

From which store do we have the highest sales?

Which outlet size has the highest sales? Does the store with the highest sales in this outlet size?

Which outlet location has the highest sales? Does the store with the highest sales in this outlet location?

Which outlet type has the highest sales? 

i)  Does the store with the highest sales in this outlet type?

**Data Source**

The datasets that we are going to use are :
Train set(Link) 
Train set description 

**Data Mining Goals**

Our data mining goals for the project are as follows:
Analyze the attributes of products. 
Analyze the attributes or the outlets/stores.
From the analysis of the attributes, find the insights to aid in decision making.
 
**Data Mining Success Criteria**

Our success criteria will be measured by finding the insights from the analysis of attributes of products and outlets that will be used for decision making.

**DATA UNDERSTANDING**

**Data Understanding Overview**

For this project, we are using the availed dataset by the company. These datasets are:
i.Train Dataset.csv - a dataset containing the data for 10 stores and 1559 products for the year of 2013.

**Data Description**

We have one main dataset available for this project. A detailed description of the dataset is provided as follows:
Train-Set Dataset - this dataset contains the product id, product types, Maximum Retail price, product visibility percentage, fat content, establishment year,	 outlet size, location type, outlet type and outlet sales.
 
**Verifying Data Quality**

There were columns with null values that we removed to have quality data.
 
**DATA PREPARATION**

These are the steps followed in preparing the data 
1. 	Loading Data 
The data was loaded in a collaborative notebook. 
2. Cleaning Data
There were columns that had irrelevant data for this project analysis that were dropped. 
The establishment year was changed to the date data type. 
Replaced null values in Outlet size with a dash.
Checked for duplicates.
Changed the casing of column names to lower.
Added an underscore between the column names that have two words or more.
Checked for uniformity in categorical column values and adjusted the wrong values on the fat content column.
Changed outlet sales and maximum retail price data type to integers.

**ANALYSIS**

The most sold product was: 
Fruits and vegetables with total sales of 2,819,435.
 
The most sold type of fat content product was:
Low Fat with total sales of 11,901,328
 
The most visible product was:
Breakfast with 8.6% visibility rate.
 
The store/outlet with the highest sales was:
 OUT027 with sales of 3,453,454
 
The medium size stores had the highest sales in 2013. OUT027 is a medium sized store.
 
The location type that had the highest sales was:
Tier 3 with total sales of 7,635,070.
The store with the highest sales was in this location type.

The outlet type with the highest sales was:
Supermarket Type3 with total sales of 12,914,551.
 
The above analysis was done using Collaborative notebook that contains both python and SQL analysis tools. The full analysis can be found in the following notebook.[link] and the management tasks of the project can be found on Trello Board(link).

**RECOMMENDATIONS**

Advanced analysis should be done to understand why OUT10 and OUT19 have very low outlet sales. 

Supermarket type 3 has the highest outlet sales. 

Grocery stores have the least amount of sales that need a keen look from the management to understand the reasons for performance and improve their sales.

Medium sized outlets have higher sales and should be considered when venturing into new locations and investment.

Location type Tier 1 which has lower sales has small-sized supermarkets and a grocery store. To increase sales, we need to add or renovate one small supermarket to medium-sized supermarket.

There is only one High-sized supermarket with significant outlet sales. From our analysis, we consider it a profitable venture. 


