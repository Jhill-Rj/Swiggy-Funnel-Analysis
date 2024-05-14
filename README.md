# Swiggy-Funnel-Analysis
Business Case: Swiggy
Swiggy is one of the largest food ecommerce platform in the country. Every day more than 1 million users are transacting on the platform.Let’s say you are growth and strategy analyst of Swiggy and you need to generate insight on company’s performance in 2019. For this you are going to use ‘Funnel Case Study Data’ workbook which has 3 work sheets. You can find the details of the sheets below:

Session Details sheet has date wise session count. You can find listing sessions, menu sessions, cart sessions, payment sessions and order sessions day over day

Channel wise traffic sheet has traffic (listing sessions) breakup at date level.

Supporting Data sheet has other information at date level which might help you solve the case. The description of the columns is written below

Metric Description
Count of restaurants: Number of operating restaurants for the day
Average Discount: Average discount given to all the transacting customers
Out of stock Items per restaurant: Average out of stock items per restaurant (total out of stock items/totalrestaurants)
Avg. Packaging charges: On an average what is the packaging charges paid by customer while placing the order
Avg. Delivery Charges: On an average what is the delivery charges paid by customer while placing the order
Avg Cost for two Cost for two is approximate spent for creating meal for two.
Number of images per restaurant: Count of images listed per restaurant on menu page
Success Rate of payments: ratio of successful transactions and payment initiated

### Your Task:

• You need to identify the increase or decrease in the number of orders using Session Details sheet

o Fill all the remaining columns of Session details based on the definition mentioned above the column names

o Identify date of highs and lows in the orders with respect to same day last week

o Hint: on weekends, Swiggy is getting extra orders naturally. Hence you might see so many highs.

o Hint: You can ignore any difference of less than 20% and above -20% in orders from the same day last week. Hence you can define highs or lows which are above 20% or lows below -20%

• Check if there is change in traffic as compared to same day last week
o If there is change in traffic, identify the source of traffic change using Channel wise traffic sheet

• Check if there is change in Overall Conversion as compared to previous dates
o Break the overall conversion into smaller part in the following metrics, and create fresh columns on the following metrics in the Session Sheet

§ L2M

§ M2C

§ C2P

§ P2O

o Identify which one of the conversions is fluctuating

o Create hypotheses on what could be the possibility for fluctuation in conversions

o Validate the hypotheses using Supporting data
