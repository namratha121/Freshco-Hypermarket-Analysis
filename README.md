# Freshco-Hypermarket-Analysis

Freshco Hypermarket, situated in HSR, Bangalore, has established itself as a prominent supermarket in the region, catering to a wide range of customers. In response to evolving customer needs and to enhance convenience, Freshco introduced a home delivery service in the year 2021. To ensure seamless operations and optimize customer satisfaction, the store diligently maintained a comprehensive transaction data sheet, containing detailed information at the order level.

Business Metrics:
Completion rate: This refers to the rate at which orders are completed (Order successfully delivered / Total orders placed).

Customer Lifetime Value: It refers to the total revenue generated per customer. 

Acquisition month: First month of transaction by the customer.

Delivery Area: It refers to the designated drop-off location where a product or package is intended to be delivered. Refer to the order geo drop column for this.

Slot definition:
A time slot is a specific interval when a customer chooses to place an order from a specific store or location.
Example of time slots: morning, afternoon, evening, night, and late-night.

Morning: Orders placed between 5 am to 12 pm

Afternoon: Orders placed between 12 pm to 5 pm

Evening: Orders placed between 5 pm to 8 pm

Night: Orders placed between 8 pm to 11 pm

Late Night: Orders placed between 11 pm to 5 am

Customer acquisition source:
It is the source from which a customer got acquired to the platform.

Overall delivery time:
It refers to the time difference between the order placed time and the completion time of the delivery process. It measures the total elapsed time required for the entire delivery process (Order time – completed delivery time).

The overall delivery time can be broken down into the following:

Order to Arrival: Order time to Partner Store reach.

Arrival to Pickup: Partner Store Reach Time to Partner Start for Delivery Time.

Pickup to Delivery: Partner Start for Delivery Time to Completed/Cancelled Timestamp

WHAT I DID : 
Order Level Analysis:
1. Identified order distribution at slot and delivery area level.

2. Identified the areas having the highest increase in monthly orders (from Jan to Sep) in absolute orders.

3. Calculated delivery charges as a percentage of product amount at slot and month level.

4. Calculated discount as a percentage of product amount at slot and month level.

5. Calculated discount as a percentage of product amount at drop area and slot level.

Completion Rate Analysis:

1. Identified completion rate at slot vs. day of the week (Sunday to Saturday) level. Can you spot some pattern in the data?

2. Calculated completion rate at drop area level.

3. Analyzed completion rate at the number of products ordered level. For this, first, you need to create a column having the number of products against every order.

Customer Level Analysis:
1. Identified completion rate at source level.

2. Calculated LTV for every customer.

3. Calculated aggregated LTV at customer acquisition source level. Refer to aggregated LTV example.

4. Calculated aggregated LTV at acquisition month level. Refer to aggregated LTV example.

5. What is the average revenue (product amount after discount) per order at different customer acquisition source levels?

6. What is the average revenue (product amount after discount) per order at the acquisition month level?

7. Identified patterns in order rating across slots, number of items placed, delivery charges, and discounts. For example:

8. Orders placed late at night may be rated high.

9. Orders placed early in the morning may not be rated high.

10. Orders with more than five items may be generally rated high.

Delivery Analysis:
1. Calculated average overall delivery time at month and delivery area level.

2. Calculated average overall delivery time at month and weekday/weekend level. You might need to create a column that tags every date as either a weekday or weekend.

3. Calculated average overall delivery time at slot level. Refer to the definition of slot.










