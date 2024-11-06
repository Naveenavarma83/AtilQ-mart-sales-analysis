AtliQ Mart Sales promotion Campaign Analysis   
Domain FMCG

Project overview & Problem statement 

AtliQ Mart (an imaginary retail giant) with over 50 supermarkets in southern region of India, ran a massive promotion during Diwali 2023 and Sankranthi 2024 ( festive time in India ) on their AtliQ branded products.
Now the sales Director wants to understand which promotions did well and which did not so they can make informed decisions for their next promotional period.

So the company wants insights for 10 ad hoc / business requests.

The database provided to me contains three dimension tables and one fact_events table.
dim_product : contains attributes like product_name, product_code &product_code.

dim_store : contains attributes like store_id & city.

dim_campaign :  contains attributes like campaign_id, campaign_name, start_date & end_date.

fact_events : contains records like event_id, store_id, product_code, campaign_id, base_price,

                      promo_type, Quantity sold before promo & Quantity sold after promo.

 DATA MODEL :

 ![image](https://github.com/user-attachments/assets/fd1964a1-22e8-4895-a0dc-60f4d85d9163)


Tools Used :

•	I used My SQL for answering adhoc questions.

•	Power BI for visualization.

Five AdHoc requests :

•	To identify high value products that are being heavily discounted, 
  we provided list products with base price > 500 and that are featured in promotype ‘BOGOF’ (buy one get one free).
  
•	To generate a report that provides an overview of number of stores in each city with 
  descending order of store count that helps in identifying cities with highest store presence.
  
•	To provide a report that displays each campaign along with their total revenue generated 
  before and after promotion which helps in evaluating financial impact of the campaigns.
  
•	To produce a report that calculates the Incremental Sold Unit % for each product category for Diwali campaign 
   along with the rankings. This information assists us in assessing product wise success and impact od Diwali campaign.
   
•	To generate a report identifying Top 5 products ranked by Incremental Revenue % across all campaigns 
  which helps in identifying most successful product in terms of Incremental revenue %.











