# MTN-SERVICE-ANALYSIS

## TABLE OF CONTENTS
- [Data_Overview](#data-overview)
- [Content](#content)
- [Data_Sources](#data-sources)
- [Observations_During_Data_Cleaning_and_Preparation](#observations-during-data-cleaning-and-preparation)
- [Findings](#findings)
- [Recommendations](#recommendations)
- [References](#references)

### DATA OVERVIEW
This is a data analysis of MTN services and sales tracking customer churn status, and an investigation will be carried out to note the general problem, which is the reason for churn, and ways to mitigate this problem. MTN is one of the network providers in Nigeria. The data is a record of customers from the period of January to March of a particular year, with a total of 974 customers. This Analysis was done with the Python language. The Following Insights were analyzed; These are:

-Count trend

* How many customers does MTN have from January to March
* What is the customers' distribution based on the month
* What is the highest-selling device?
* What is the customers' distribution based on Gender
* What is the count of Customers based on Location?
* What is the percentage of customers' Status

-Period Trend
- * 1. What month did MTN have a decline in most
- * 2. Number of Customer registrations based on location
- * 3. What location has the highest revenue

-Rating Trend
- * 1. How is the customer's Rating based on the state?
- * 2. Does the rating have a significant effect on the reason for churn based on location?
- * 3. What is the total reason for churn based on location?

 ### CONTENTS
 
 - The dataset comprises the following: 974 rows and 17 columns. In the 17 columns, we have the following headers;
 * a. Customer ID: 
 * b. Full Name: This column contains the full name of customers who
      were registered with MTN.
 * c. Date of Purchase: This is the date registration was made
      for the customer using the MTN device.
 * d. Age: This is the Age of a particular customer.
 * e. State: This is the state of registration.
 * f. MTN Device: This is an MTN product that was sold to a customer at
      a particular period.
 * g. Gender: This is the column that distinguishes the male and
      female customers.
 * h. Satisfaction Rate: This is the column that shows how the
      customers rate MTN services that they
      are using. The rating is from 1 to 5
 * i. Customer Review: This is the column that shows how the
      customers review MTN services with the following: Poor, Fair, Good,
      Very good, Excellent.
 * J. Customer Tenure in months: This column has to do with how long
      A particular customer registered uses a particular MTN Product
 * k. Subscription Plan: This is the column that shows the network plan
       a particular customer subscribed to.
 * l. Unit Price: This is the price per device owned by the MTN
      network provider
 * m. Number of Times Purchased: This is the number of times the device
      was sold to a particular customer.
 * n. Total Revenue: This is the total sales for devices sold by quantity.
 * o. Data Usage: This is the column for data usage by the customer.
 * p. Customer Churn status: This is the column that indicates if
      the customers are still active or not. The "Yes" is not Active
      and "No" is still active.
 * q. Reasons for Churn: This is the column that speaks to the reason
      a customer stops using MTN service.

 ### DATA SOURCES
 This is a comma-separated value (CSV) file.

 ### OBSERVATIONS DURING DATA CLEANING AND PREPARATION
 - Null values in the data were checked to ensure the dataset is okay for analysis. Out of 974 Reasons for Churn, 690 rows were null, and from the investigation, the customers in those rows were still active.
- All null values in the Reason for churn status were replaced with "Active"
- Splitting the column "Date of Purchase" into "Day of Purchase" and "Month of Purchase".

 ### FINDINGS

 - The Total Revenue on sale from the period January to March is N199,348,200

 - The Month with the highest number of customers is February, with 450 registered customers. The others
    are  January with 271 customers and March with 253 customers.
   
 - The Month with the Most decline in customers is February, with a 31% decline, next by March with a
    30.4% decline and January with a 23.9% from customers that were registered in each month.
   
 - The State with the Highest number of customers is Osun, with 43 customers registered, next is Abuja with
   42 customers registered. And the state with the fewest customers is 14 customers registered.
   
 - The State with the highest decline in customers is Abuja, with 15 customers out of 42 customers, while
   the State
   
 - The MTN device that was sold from this period (January to March) are Listed from the highest to the least respectively; Mobile Sim Card with a total of 301 customers, 5G Broadband Router with a total of 229 customers, Broadband MiFi with a total of 228 and 4G Router with a total of 216 customers.

 - The gender that patronizes MTN the most is the Female with a 50% patronage to the male with 49.2%.

 - The State with the highest revenue so far is Plateau State with a Revenue of N













