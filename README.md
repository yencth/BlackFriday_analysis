# BlackFriday_analysis
* A retail company wants to understand the customer purchase behaviour (purchase amount) against various products of different categories. We will use the data of Black Friday and analysis this data. This is the link you can download data set:

* The library use: numpy, pandas, matplotlib, seaborn, sklearn.
Data use is file train.csv. 
* The data contains customer demographics (age, gender, marital status, city_type, stay_in_current_city), product details (product_id and product category) and Total purchase.
* We will analysis the data to find the insight for Sale Strategy in the next Black Friday by use the historical data.

## Files description
* README.md: 
* train.csv: the csv file which contains the data used in the analysis process.
* Black Friday Data analysis.ipynb: jupyter notebook. It contain python code and process of data analysis, visualization and modeling.
* requirements.txt: The libraries need to be installed 

## Summary of the results
### Question 1: Who should be the target customer in the next campain?
* In the next marketing campaign, we are more interested in men, because the percentage of men buying is 75%.
* City B has the most purchases. Focus on this customer. Or we should have coupon for city A, C to attract customers to buy more.
* We have to care about people who are within a year in the city because they have more purchases than others.
* We should take care of singles in our next marketing campaign.
* The age group 26-35 buys the most of the age groups. Attention should be paid to this age group.

### Question 2: Which product should be cared in the next campain?
 * Purchase is heavily influenced by Product Category.
 * The most purchased products are 5, 1, 8 in Product_Category_1, should be displayed at the front of the store to increase sales.
 * There is a clear difference between the product types in Product_category_1 in price varience, so depending on the company's strategy towards which price to choose the right product.
 
### Question 3: Which products are best selling ?
* The first product sold 28 million with the number of 1615, the second product was 26.7 million with the number of 1612. The highest sales product also had a higher price.
* The 3rd product sold in quantity of 1383, lower than the 4th product, but the 4th product had a lower price than the 3rd product, so even though the quantity was larger, the purchase was still lower than the product 3rd
* P00265242 best selling with most age groups.
* Age group 18-35, 46-55+ buy this product the most.
* The group 0-17 years old bought the most P00255842, 36-45 bought the most P00025442.

This is link of blog:https://yencth1.blogspot.com/2023/03/what-is-your-strategy-for-black-friday.html
## Acknowledgements
Dataset: https://datahack.analyticsvidhya.com/contest/black-friday/
