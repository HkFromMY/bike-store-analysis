# Problem Statement
![image](https://github.com/HkFromMY/bike-store-analysis/assets/48499555/33b85297-12db-4056-ac13-33357e16214e)
Trek Bikes corporation is a popular bicycle manufacturing and retailer company that started their business in 1976, Waterloo, Wisconsin with over 40 years of operation to date. To make biking more accessible to the community, this business is started to make the bicycle available to more people with lower price and better quality so that everyone can enjoy biking as sport or entertainment without stressing too much on the cost. Therefore, the very core value of the company is to be innovative in creating the products to provide the best quality for the customers while preserving the environment as much as possible for sustainable goals. To further increase the business visibility in its E-commerce platform to more customers for larger market share, BI system is implemented to utilize the available data generated via the E-commerce platform to construct data-driven business strategies. 

# Tools Used
1. Microsoft Visual Studio Community 2019
2. Microsoft SQL Server Analysis Service (SSAS)
3. Microsoft SQL Server Management Studio (SSMS)
4. Power BI Desktop

# Assumptions Made
1.	As the objective stated, only the sales generated via E-commerce platform of Trek Bikes will be measured so the sales generated through reseller channel will not be taken into the dashboard creation.
2.	All data visualizations are generated based on the dataset from 2010 to 2014 as the dataset does not contain sale records from 2014 onwards.
3.	Inventory changes in Trek Bikes will take reseller’s stock into consideration as well because it does not affect the accuracy of the analysis.

# Hypothesis Made
1.	With more promotions and marketing, the sales amount can be increased.
2.	Promotion events such as discount is the most important factor behind customer’s purchase decisions. 
3.	Accessories products will have higher popularity, thus generating the highest sales amount.
4.	With the launch of accessories products, the bike product’s sales can also be increased as accessories products can attract more new customers to explore the store. 
5.	Customer who has children will be more likely to buy bikes as compared to those who do not because they purchase the bike as gift.
6.	Customers with higher yearly income will contribute to more sales and profit. 
7.	Customers with more cars will be less likely to purchase bike products.
8.	Customers that have lower commute distance tend to purchase bikes and its related products more as compared to other customers with higher commute distance. 
9.	Some categories of the product are more popular for the customer base so more investment should be given to those products.
10.	The lower the commute distance, the higher the demand for the bike as bike is more convenient than car.

# Findings & Recommendations
## Sales Dashboard
![image](https://github.com/HkFromMY/bike-store-analysis/assets/48499555/c48c6b23-01cd-4f05-8c63-f1a984bcac77)
**Analysis:**
1. There is a big increase from 4th quarter of 2012 to 2013 in terms of sales amount and the number of orders placed which is because of the distribution of promotional events and new product launch. 
2. The other reason to the great increase in the sales amount is also because of the US government's planning to expand the bicycle routing system.
3. United State is the largest market for Trek Bikes by examining the total orders placed and the sales amount generated.
4. Price is the main factor behind the customer's purchase decision, followed by the promotions, product's manufacturer, and quality. 

**Recommendation:**
1. Conduct seasonal promotional events (monthly promotions) on different products or new products.
2. Adjust the pricing of the products after conducting a comprehensive competitor analysis to price the products appropriately.
3. Collaborate with reputable manufacturers to increase the quality of the product delivered to the customers.

## Product Dashboard
![image](https://github.com/HkFromMY/bike-store-analysis/assets/48499555/a6cea9c1-41b0-42bb-86b9-150b114878a6)
**Analysis:**
1. There is good stocking management and practices because the number of units in and out are close to each other which indicates that there is no overstocking issues. There is also seasonal pattern in the units out which can be used to predict and forecast the number of units that will be stocked into the warehouse.
2. New product launched, which is the accessories type of products that are affordable purchased by more customers which leads to the increase in popularity and exposure of the Trek Bikes. 

**Recommendations:**
1. Re-stock the products every 2 months to avoid overstocking issues and ensure that there is enough supply to satisfy the customer's needs.
2. Launch package that bundle the accessory products with other type of products such as bikes and clothing to utilize the popularity of the accessory products to expand more opportunities to the other products.
3. Conduct promotional events for clothing products due to their low popularity and sales.

## Customer Dashboard
![image](https://github.com/HkFromMY/bike-store-analysis/assets/48499555/3fa428dd-d222-45fa-af58-4176c6cfcd92)
**Analysis:**
1. Customer with lower commute distance orders more items from Trek Bikes as they may use the bicycle as the main transportation method.
2. The customers start losing interest in bicycle products when they own more than 2 cars.
3. Parent group of customers tend to have lower spending power on the bicycle products.
4. Average yearly income does not relate directly to the spending power on bicycle products because customer's free time are also related as well. When the average yearly income of the customers decreases, then the spending power of the customers also decreases. However, there is an exception, which the customers that are managers tend to buy less from Trek Bike. This is inferred that they have less time to spend time in recreational activities with bicycle nor using the bicycle as transportation tools as they lack of time.

**Recommendations:**
1. Target customer group with lower commute distance in United State with social media platform by posting related tips that helps the customer to spike interest in using bicycle as the main transportation tools.
2. Highlight the benefits of cycling as compared to driving in advertisement to target the customer groups that use car as the main transportation methods.
3. Promote bike as gift to children with discount packages to help parent with less spending power to afford the bike products.

