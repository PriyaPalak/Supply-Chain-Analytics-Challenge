# :truck: Codebasics Supply Chain Analytics Challenge

## :muscle: About the Challenge

This is the 2nd Challenge by the CodeBasics team.

AtliQ Mart is a growing **FMCG manufacturer** based in the state of Gujrat. It is currently operational in three cities Surat, Ahmedabad and Vadodra. They want to expand to other metro/tier1 cities in the next 2 years. But they are facing issues in providing proper customer service, like the **deliveries being delayed** and **not being made in full**. Before expansion, they want to fix these issues. So, the company wants the Supply Chain Analytics team to **track the service level for all the customers on a daily basis** so that they can swiftly respond to these issues.

Being a part of the Supply Chain Analytics team, design a dashboard to track the relevant metrics mainly **OT %** (on-time delivery), **IF %** (In-full delivery) and **OTIF %** (On-time In-full delivery) against the target level set for each customer.

## :books: About the Data

You are provided with 6 tables containing data from 6 months - March to August.

- dim_customers: contains customer_id, their name and the city they belong to. In total, the company has **35 retail stores** as its customers in the 3 cities.
- dim_products: contains product_id, its name and the category it belongs to. The company is manufacturing **18 products** across **3 categories** namely Dairy,Food and Beverages.
- dim_date: contains order_placement_date, month and week number.
- dim_targets_orders: contains cutsomer_id and OT, IF AND OTIF delivery target percentages for each customer
- fact_order_lines: contains order_id, order_date, customer_id, product_id, ordered_quantity, agreed_delivery_date, actual_delivery_date,delivered_quantity and whether it was delivered in-full, on-time and on-time in-full. It contains more than **57000 records** at **product level**.

- fact_orders_aggregate: contains order_id, customer_id, order_date and whether the order was delivered on-time, in-full and on-time in-full. It contains more than **31000 records** at the **order level**.



## :bar_chart: Dashboard

Built a 3-pager Dashboard using Tableau.

Tableau: [Link](https://public.tableau.com/app/profile/priya.palak7639/viz/FMCGChallenge/Story1)

![FMCG 1 1](https://user-images.githubusercontent.com/96012488/207310165-4cbd1484-3996-464e-960f-afdbf6be4995.png)

![FMCG 2](https://user-images.githubusercontent.com/96012488/207309545-b2793bff-3f53-458a-947f-5de30400bb89.png)

![FMCG 3](https://user-images.githubusercontent.com/96012488/207309574-0b3231ae-c701-42e0-ac01-fcfc4e5192bd.png)



