# WM_portfolio
Data analyst porfolio


# [Project: Sample Food Delievey Assignment](https://github.com/wndmiao/WM_portfolio/blob/main/Doordash_Sample_deliveries_data_-_1_month_Final%20version.xlsx)
The Data: 
Customer placed order datetime
Placed order with restaurant datetime
Driver at restaurant datetime
Delivered to consumer datetime
Driver ID
Restaurant ID
Consumer ID
Delivery Region
Is ASAP
Order total
Amount of discount
Amount of tip
Refunded amount
![](/image/Doordash_Sample_deliveries_data.jpg)

Quick Note:
About the data: The original Raw Data is saved on Raw_Data tab. I cleaned up the data on Edit_data tab by:

 1) assigned the month and year (since Dashmart was instroduce in Aug, 2020, I picked 08/2020 as mm/yyyy). Some of the data with Customer placed order datetime on 31st of the month and Customer received order on the 1st. I  updated these Customer received order datetime to the next calender date. 

 2) Some of the data has null value on datetime. I kept the null value cell as blank on Final_data tab, beacause other data besides null value are still useful to conduct analysis. 

3) Most of the calculation are done on the Excel, only a few calculation are calculated using MySql Workbench

*Recommendation: To keep the data accurate and consistent, I would recommend re-formated the datetime columns and fix the null value

Insight 1: Location
![](/image/Location.jpg)
Location plays a huge role in attracting customers. Based on the pie chart above, Palo Alto has 63% of the total order, which is more than the combination of San Jose 16% and Mountain View 21%. Average amount per order for Palo Alto and Mountain View are similiar at the Price of $52. San Jose has lower average order amount. Location has an impact on people's lifestyle. Good location decisions can significantly boost a company's long-term performance. 

Insight 2: Merchants
![](/image/Merchant.jpg)
Some restuarants tend to have more demand than others. For instance, Restuarants with ID 8, 20 and 9 had more than 700 orders in a month, which is equal to 22-23 orders a day. To understand why these restuarants are more succeessful, we can look into the food quality, types of business, restuarant menus, packaging, customer rating, etc. 

Insight 3: Customers
![](/image/Customer.jpg)
More loyal customers mean high profits. A loyal customer has positive experience with the business and willing to purchase repeatedly from your business verse your competitors. According to the chart above, the top  1 cutomer(customer ID 514) has ordered 66 times in a month, roughly twice a day.  Keeping the loyal customers is important. Base on the customer retention measurement, customer retention is 5- 25 times cheaper than new customer acquisition (advertising).

Insight 4: Drivers
![](/image/Dasher.jpg)
The top Driver has delievered 257 orders in a month, equal to 8.3 orders per day. Base on the average time, 47 minutes per orders, this dasher worked 6.2 hour daily. 

Insight 5: Time Delivery
![](/image/Delievery.jpg)
On average, the time from customer placed order to order received by restaurant is 8 minutes, the time from restuarant prepared the order to driver picked up is 15 minute, the time from driver picked up to delievered is 25 minutes. As a result, the average of deliveries time is 47 miunutes. Shorten the delievery time in any of the process can significantly improve the business.

Insight 6: Days 
![](/image/image/day1.jpg)
![](/image/image/day2.jpg)
The daily orders is between 500-700 orders. On 23rd to 28 of the month, orders increased slightly, range between 600 to 700.Compare to weekdays, weekends generate more 

Summary and Recommendation: 

1) Location: location can play a key factor. Expanding business to cities that has higher population and leisure life style(i.e. Palo Alto) can boost business revenue. 

2)  Merchant & food quality: A good restuarant always have high quality food and well packaging. Customers who like the food and have positive customer experience are more likely to turn into glowing online reviews and repeat business, which can attrack more customers, and more revenue. 

3) Know your customer: Customer is the core of the business. understanding the customers that might place orders makes it easier to make recommendation to meet their needs. For example, What are they hoping to get out of the experience?  What are their food perference? And How likely they would refer friend to this business? 

4) Promotions & reward program:  Promotions and loyalty programs can encourage customers to order food delivery more often. We may consider having promotion for customers during the slow days (i.e. Wednsday to Friday) in order to avoid the busy traffic.

5) Incentices: Incentice motivate drivers. We can consider rewarding and recogning dashers who reach goals in a set amount of time.

End


# [Project: Building a Finance Interactive Dashboard with Excel](https://github.com/wndmiao/WM_portfolio/blob/main/Finance%20expense%20intereactive%20dashboard.xlsx)

The Data:                                                                                                      
Headline Figures and Images                                                                        
Doughnut Chart                                                                                          
Dual Column Chart                                                                                     
Line Chart                                                                                
Treemap Chart                                                                          
Waterfall Chart
Top 5 Conditional Formatting Data Bars                                                                           
Create connection report to link the slicers                                                                                 
Create connection report to link the slicers and chart title                                         
![](/image/Dashboard.PNG)

# [Project: Build a dashboard to show the death rate of Covid](https://public.tableau.com/app/profile/wendym4423/viz/CovidDashboard_16582091798820/Dashboard1)
1-Measuring the covid cases and death counts per continent and country     
2-Calculating the percentage of death rate over cases and country population        
3-Finding the trend of the death rates                 
![](/image/map.png)
![](/image/chart.PNG)

# [Project: Product Subscription overview](https://public.tableau.com/app/profile/wendym4423/viz/ProductSubscriptions/Subsription)
Data source:                                                      
4 tables                                                              
    1. Cuatomer cases: includes case ID, date_datetime,customer_ID, channel, reason                                          
    2. Customer Info: includes customer_ID, age, gender 	                                                                                                 
    3. customer product: includes customer_ID , product, signup_date_time, cancel_date_time                    	     
    4. Product_info: includes product_ID, name, proce, billing_cycle                                         	
    
Data cleaning: remove duplicates, format text, trim space, format number to int, convert string to datetime

Questions:
-Finding the percentages of monthly vs annually subscription.                                                                                                         	
-Finding the signup amount vs cancel amount over years, and the trend. 	                                                                      
-What age range and gender are most likely to subcribe the product?                                                     	                      
![](/image/Capture2.PNG)	







