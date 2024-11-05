# ShopNext PowerBI Dashboard Report
## Introduction:
ShopNest stands as the leading department store in the e-commerce marketplaces in Portugal. Serving as a seamless link, it connects small businesses from various regions in Portugal to channels, streamlining the process with a single point of contact.
We designed a comprehensive Power BI dashboard to address key business analytics for a retail dataset. We made a report of that dashboard with questions, visualizations and explanations.  

## Picture of the Dashboard
![image](https://github.com/user-attachments/assets/a49157bd-536c-4e7e-a403-12abb3fbe9dc)
![image](https://github.com/user-attachments/assets/1a6b4fcb-9fc9-4804-80df-b8d6f2608189)

## Question 1:
**Identify the rating distribution in the Shop_Nest dataset, showcasing ratings categorized as Excellent, Very Good, Good, Bad and Very Bad, along with corresponding orders.**  
## Visualization:
![image](https://github.com/user-attachments/assets/91e777a0-87b2-4ed5-948b-7fd5238b7bb7)
## Explanation:
The bar chart illustrates the distribution of ratings within the ShopNest dataset.                 
Categories like “Excellent” and “Very Good” show many orders, suggesting customer satisfaction. Conversely, lower ratings like “Bad” and “Very Bad” show fewer orders, highlighting areas for potential improvement.  
This setup will help you visualize and understand the rating distribution in the ShopNest dataset effectively. 
## Question 2:
**What are the top 10 and bottom 18 most popular product categories in the ShopNest dataset? Please list them based on the number of orders.**
## Visualization:
![image](https://github.com/user-attachments/assets/62ebfa36-a063-47aa-9b90-63616548223b)
![image](https://github.com/user-attachments/assets/4ee1c162-6853-4ae2-9c9c-b1445e9c9b6f)
## Explanation:
- **Top 10 Product Categories:** The bar chart displays the top 10 most popular product categories based on the number of orders, indicating high customer demand and preference. These categories are crucial for driving sales and should be the focus of marketing strategies to maximise revenue.
- **Bottom 18 Product Categories:** The bar chart also highlights the bottom 18 product categories with the lowest number of orders. This insight can guide inventory management and promotional efforts to boost sales in these categories or reconsider their stock levels to optimise space and resources.
- This thorough analysis provides a clear view of product performance, helping in strategic planning and decision-making to enhance business outcomes.
## Question 3:
**List the total number of active sellers by yearly and monthly.**
## Visualization:
![image](https://github.com/user-attachments/assets/d314a1be-5cd3-405f-a8c0-91272a916e3c)
![image](https://github.com/user-attachments/assets/11541616-7a8b-4fec-ab42-46b219ecd89f)
## Explanation:
- **Yearly Active Sellers:** The line chart indicates a consistent decline in the number of active sellers from 2018 to 2020. This downward trend could be due to various factors such as market saturation, increased competition, or external economic conditions.
- **Monthly Active Sellers:** The bar chart breaks down the number of active sellers per month. This visualization helps identify seasonal trends or promotional impacts on seller activity. For example, a spike in August reflects increased seller engagement during holiday seasons, while a dip in September might indicate an effect of external factors like lockdown or off-peak periods.
## Question 4:
**Which payment methods are most commonly used by ShopNest customers?**
## Visualization:
![image](https://github.com/user-attachments/assets/dc67b142-ed73-4ab6-8ae9-6079b0a01be6)
## Explanation:
- **Credit Card (76.51k, 75.24%):** Credit cards are by far the most popular payment method among ShopNest customers, representing over three-quarters of all transactions. Continue to streamline the credit card payment process and offer exclusive promotions and rewards for credit card users.
- **Boleto (19.78k, 1.46%):** Despite being a traditional payment method, Boleto still holds a small portion of the total transactions.
- **Voucher (3.87k, 3.8%):** Vouchers are used by a small but significant portion of customers. This method is often employed during promotional campaigns and gift purchases, indicating its role in marketing strategies.
- **Debit Card (1.53k, 1.5%):** Debit cards, while secure and direct, account for a relatively small portion of transactions. The lower percentage could be due to customers preferring credit cards for their deferred payment options and rewards. However, maintaining robust support for debit card payments ensures inclusivity for all customers.
## Question 5:
**Identify the product category-wise profit margin using the formula**
## Visualization:
![image](https://github.com/user-attachments/assets/7ee09bc0-7b65-48b6-ad21-6c74c185aff3)
## Explanation:
- The Matrix shows the profit margins for each product category.
- The formula used to calculate profit margins is :  
(Payment value – price +Freight_value)/payment_value*100
## Question 6:
**Determine the monthly payments made by customers using credit cards.**
## Visualization:
![image](https://github.com/user-attachments/assets/02b7ac32-b1d8-4823-8ae3-c3edbadd5e78)
## Explanation:
- **Mid-Year Peak:** The highest number of payments occurs in July, which might indicate seasonal promotions, summer sales, or consumer behaviour patterns related to holidays or events. Retailers could explore leveraging this period further through marketing or discounts.
- **End of Year Drop:** After peaking mid-year, there's a significant drop in payments toward the end of the year, particularly in September, with only a slight recovery toward the holidays in November. This could indicate a reduction in spending during this period or perhaps a shift toward other payment methods.
- **Seasonal Promotions:** Given the peak in mid-year, the business could benefit from identifying specific events or sales that drive this spike in credit card payments. They can capitalize on this trend by scheduling future campaigns around similar times.
- **Address the Decline:** The sharp drop after July and the particularly low figures in September suggest a need to explore strategies to maintain customer engagement and spending during these months.
## Question 7:
**Identify sellers categorized by city, excluding cities starting with the letters S and B.**
## Visualization:
![image](https://github.com/user-attachments/assets/78bf0124-5fde-4200-b9f8-8e90e91c3555)
## Explanation:
- The stacked column chart shows the number of active sellers in various cities, excluding those starting with "S" and "B". This visualization helps identify the geographic distribution of sellers in a more detailed and filtered manner.
- The chart reveals that cities like Curitiba, Rio de Janeiro and Ribeirao preto have a high concentration of active sellers. These cities are major urban centres with bustling markets and high demand, making them attractive for sellers.
- Ensuring balanced geographic coverage can help optimize logistics and customer reach. Supporting sellers across a diverse range of cities can enhance market penetration and customer service.
## Question 8:
**Create a dynamic visual that compares the number of delayed orders to the number of orders received earlier for each month. Utilize the drill through the cross-report feature to provide a detailed analysis of late and on-time deliveries.**
## Visualization:
![image](https://github.com/user-attachments/assets/65826a3b-e64f-4e57-ba7b-78723178376b)
![image](https://github.com/user-attachments/assets/22d5994f-ed23-4791-9fc0-c040a27e9110)
![image](https://github.com/user-attachments/assets/ded2b385-e74f-4685-bcd9-197edd307aff)
## Explanation:
- The clustered column chart dynamically compares the number of delayed orders to the number of on-time orders for each month.
- By comparing on_time and delayed orders, businesses can monitor performance and identify areas needing improvement.
- Drill Through is added for cross-referencing, you will have more details on order ID, delivery status, review category, number of days from the expected delivery date the delivery arrived, and payment methods.
## Slicer:
![image](https://github.com/user-attachments/assets/b6b77372-7951-4e33-9fe6-9e5cc002e170)  
To allow for focused analysis across different periods, a slicer has been incorporated into the dashboard. This feature enables users to filter data specifically for the years 2016, 2017, and 2018.








