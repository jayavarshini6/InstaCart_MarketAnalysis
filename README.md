# InstaCart_MarketAnalysis


## Insta Cart - Grocery Made Easy !!



![image](https://github.com/jayavarshini6/InstaCart_MarketAnalysis/assets/86217885/a6067c81-8520-40dd-a727-cf92ee36ca8e)

* We all know use Insta Cart for Grocery Shopping one of the top grocery platform in america with $17 billion net worth and it is famous for making life easy for millions of americans.

* Main business Idealogy of Insta Cart is simplyfying grocery shopping through online platform.

* Personalising shopping experience for each user makes insta cart business model succesful.

## Features Analysed in this project



### 1. Perform customer segmentation based on purchasing patterns in the grocery dataset to identify groups of customers with similar buying habits.
### 2.Utilize keyword searches and customer cart products to generate personalized product recommendations.

## Dataset



### The data contains 3 million grocery orders from 200,000 Instacart users. For safety purpose data follows General Data Protection Regulation (GDPR) - Regulation (EU) 2016/679 which prohibits use of customers personal information.

### Tabels used:

### aisels.csv


#### aisle_id,aisle  
1,prepared soups salads  
2,specialty cheeses  
3,energy granola bars  
...


### departments.csv


### department_id,department  
1,frozen  
2,other  
3,bakery  
...


### order_products__*.csv
#### These files specify which products were purchased in each order. order_products__prior.csv contains previous order contents for all customers. 'reordered' indicates that the customer has a previous order that 
#### contains the product. Note that some orders will have no reordered items. You may predict an explicit 'None' value for orders with no reordered items. See the evaluation page for full details.
#### order_id,product_id,add_to_cart_order,reordered
1,49302,1,1

1,11109,2,1

1,10246,3,0

…


### orders.csv
#### This file tells to which set (prior, train, test) an order belongs. You are predicting reordered items only for the test set orders. 'order_dow' is the day of week.

#### order_id,user_id,eval_set,order_number,order_dow,order_hour_of_day,days_since_prior_order

2539329,1,prior,1,2,08,

2398795,1,prior,2,3,07,15.0

473747,1,prior,3,3,12,21.0
…


### products.csv
#### product_id,product_name,aisle_id,department_id
1,Chocolate Sandwich Cookies,61,19  
2,All-Seasons Salt,104,13  
3,Robust Golden Unsweetened Oolong Tea,94,7  
...

