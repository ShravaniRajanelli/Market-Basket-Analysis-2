# Market-Basket-Analysis

Market basket analysis is a strategic data mining technique used by retailers to enhance sales by gaining a deeper understanding of customer purchasing patterns. This method entails the examination of substantial datasets, such as historical purchase records, in order to unveil inherent product groupings and identify items that tend to be bought together. 
By recognizing these patterns of co-occurrence, retailers can make informed decisions to optimize inventory management, devise effective marketing strategies, employ cross-selling tactics, and even refine store layout for improved customer engagement.
For example, if customers are buying milk, how probably are they to also buy bread (and which kind of bread) on the same trip to the supermarket? This information may lead to an increase in sales by helping retailers to do selective marketing based on predictions, cross-selling, and planning their ledge space for optimal product placement.

## How Does Market Basket Analysis Work?

1) Collect data on customer transactions, such as the items purchased in each transaction, the time and date of the transaction, and any other relevant information.
2) Clean and preprocess the data, removing any irrelevant information, handling missing values, and converting the data into a suitable format for analysis.
3) Use association rules mining algorithms such as Apriori to identify frequent item sets, sets of items often appearing together in a transaction.
4) Calculate the support and confidence for each frequent itemset, which expresses the likelihood of one item being purchased given the purchase of another item.
5) Generate association rules based on the frequent itemsets and their corresponding support and confidence values. Association rules express the likelihood of one item being purchased given the purchase of another item.
6) Interpret the results of the market basket analysis, identifying which items are frequently purchased together, the strength of the association between items, and any other relevant insights into customer behavior and preferences.
7) Use the insights from the market basket analysis to inform business decisions such as product recommendations, store layout optimization, and targeted marketing campaigns.

  ## Applications of Market Basket Analysis

  |**Industry**|**Applications of Market Basket Analysis**|
  |--|--|
  |Retail|	Identify frequently purchased product combinations and create promotions or cross-selling strategies|
  |E-commerce	|Suggest complementary products to customers and improve the customer experience|
  |Hospitality|Identify which menu items are often ordered together and create meal packages or menu recommendations|
  |Healthcare|	Understand which medications are often prescribed together and identify patterns in patient behavior or treatment outcomes|
  |Banking/Finance|	Identify which products or services are frequently used together by customers and create targeted marketing campaigns or bundle deals|
  |Telecommunications	|Understand which products or services are often purchased together and create bundled service packages that increase revenue and improve the customer experience|

## Association Rule for Market Basket Analysis

Market basket analysis mainly works with the ASSOCIATION RULE {IF} -> {THEN}.

**IF** means **Antecedent**: An antecedent is an item found within the data
**THEN** means **Consequent**: A consequent is an item found in combination with the antecedent. 

With the help of these, we are able to predict customer behavioral patterns. From this, we are able to make certain combinations with offers that customers will probably buy those products. That will automatically increase the sales and revenue of the company.

With the help of the Apriori Algorithm, we can further classify and simplify the item sets which are frequently bought by the consumer.

There are three components in APRIORI ALGORITHM:

* SUPPORT
* CONFIDENCE
* LIFT

Now take an example, suppose 5000 transactions have been made through a popular eCommerce website. Now they want to calculate the support, confidence, and lift for the two products, let’s say pen and notebook for example out of 5000 transactions, 500 transactions for pen, 700 transactions for notebook, and  1000 transactions for both.

SUPPORT: It is been calculated with the number of transactions divided by the total number of transactions made,

Support = freq(A,B)/N

support(pen) = transactions related to pen/total transactions

i.e support -> 500/5000=10 percent

CONFIDENCE: It is been calculated for whether the product sales are popular on individual sales or through combined sales. That is calculated with combined transactions/individual transactions.

Confidence = freq(A,B)/freq(A)

Confidence =   combine transactions/individual transactions

i.e confidence-> 1000/500=20 percent

LIFT: Lift is calculated for knowing the ratio for the sales.

Lift= confidence percent/ support percent

Lift-> 20/10=2 

When the Lift value is below 1 means the combination is not so frequently bought by consumers. But in this case, it shows that the probability of buying both the things together is high when compared to the transaction for the individual items sold. 

With this, we come to an overall view of the Market Basket Analysis in Data Mining and how to calculate the sales for combination products. 

This repository provides a set of tools and resources for performing Market Basket Analysis. Whether you are a data scientist, analyst, or business owner, this toolkit aims to simplify the process of extracting insights from your transactional data.
