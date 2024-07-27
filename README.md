# Instacart-Grocery-Basket-Analysis
Instacart, an established online grocery store operating through an app, seeks to uncover detailed insights into their sales patterns to optimize their strategy. With robust sales figures already in place, the goal is to delve deeper into the data to understand customer behaviors and trends better.

![image](https://github.com/user-attachments/assets/1f756f0e-c0c0-4d09-9d1f-e24bcc9083f2)

Regional Segmentation and Customer Analysis for Instacart

1. Regional Segmentation:

Using the customer data set, I created a new column "Region" based on the "State" column. The regions were categorized according to the information provided in the Wikipedia article on U.S. regions. This allowed for a detailed analysis of customer behavior across different geographic areas.

2. Spending Habits by Region:

By crossing the newly created "Region" variable with the spending flag, we identified differences in spending habits across regions. Customers in the Northeast and West regions showed higher average spending compared to those in the Midwest and South. This information is crucial for tailoring marketing strategies and optimizing regional operations.

3. Exclusion of Low-Activity Customers:

To focus on high-value customers, an exclusion flag was created for low-activity customers (those with fewer than 5 orders). These customers were excluded from further analysis to ensure the data set reflects the most engaged users. The filtered data set was then exported for further analysis.

4. Customer Profiling:

A profiling variable was created based on age, income, certain goods in the "department_id" column, and the number of dependents. Additionally, "orders_day_of_week" and "order_hour_of_day" were used to enhance the profiles. This helped in identifying distinct customer segments such as "Young Parent," "Single Adult," "Middle-Aged Professional," and "Senior."

Visualization of Profiles:

Below are the visualizations representing the findings:

Age Group Distribution Pie Chart:

![image](https://github.com/user-attachments/assets/53d4b00a-72b2-429f-846d-5d308bfdd317)


This chart shows the distribution of customers by age group, highlighting that middle-aged adults form the largest customer segment.

Age vs. Number of Dependents:

![image](https://github.com/user-attachments/assets/94078237-ba8a-469f-bcab-0e5f61b9bd88)


This graph illustrates the relationship between age and the number of dependents, showing variations across different age groups.

Order Frequency by Hour:

![image](https://github.com/user-attachments/assets/140d0514-fb64-4321-9e03-7108e019619e)


The histogram displays peak ordering hours, indicating high activity during late mornings and early afternoons.

Orders by Day of Week:

![image](https://github.com/user-attachments/assets/1fcafce6-b5f1-4ced-a5d6-40f82a2e971c)


This chart highlights the distribution of orders throughout the week, with weekends being the busiest.


Average Prices by Age Group and Department:

![image](https://github.com/user-attachments/assets/a53c765c-c5a1-44bb-9e34-a680272d1a20)


The bar chart compares average prices paid by different age groups across various departments.

Change in Spending Power over Age:

![image](https://github.com/user-attachments/assets/bd754654-176f-421d-9eb3-007c47e3e299)

![image](https://github.com/user-attachments/assets/6e6f2b77-fb9d-441d-a329-aa0c4077e2fe)


This scatter plot shows how spending power changes with age, providing insights into financial behaviors across different age groups.

Change in Price over Hours of the Day:

![image](https://github.com/user-attachments/assets/1a1b1188-4a93-46da-b5d9-aa6e0cf35633)


This line graph illustrates price variations throughout the day, helping to identify optimal pricing strategies.

5. Aggregated Variables and Customer Profile Analysis:

The max, mean, and min variables for usage frequency and expenditure were aggregated at the customer-profile level. This analysis revealed that "Young Parents" and "Middle-Aged Professionals" have higher usage frequencies and expenditures compared to other profiles.

6. Regional and Departmental Comparison:

By comparing customer profiles with regions and departments, distinct behaviors were identified. For example, customers in the West region tend to spend more on organic and health-related products, while those in the Midwest prefer bulk and canned goods.

Conclusion:

These analyses and visualizations provide valuable insights into customer behavior, enabling Instacart to tailor marketing strategies, optimize regional operations, and improve overall customer satisfaction. The final data set and scripts were exported and saved for future reference.
