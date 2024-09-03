### Retail Sales and Customer Behaviours Analysis
1. About Dataset
   - Data source: https://www.google.com/url?q=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Futkalk%2Flarge-retail-data-set-for-eda 
   - Number columns of dataset:  78 
   - Number rows of dataset:  1000000 
2. Transaction Analysis
   - transaction_id: Unique identifier for each transaction.
   - transaction_date: Date of the transaction.
   - product_id: Unique identifier for each product.
   - product_category: Category of the product (e.g., Electronics, Clothing, Groceries).
   - quantity: Quantity of the product purchased.
   - unit_price: Price per unit of the product.
   - discount_applied: Discount applied on the transaction.
   - payment_method: Payment method used (e.g., Credit Card, Debit Card, Cash).
   - store_location: Location of the store where the purchase was made.
   ![image](https://github.com/user-attachments/assets/0d2020d6-2dc6-4c48-a011-76e69a84dcd0)
* In the first half of the year, discount codes and revenue tend to move in the same direction. However, in the second half of the year, they move in the opposite direction. This suggests that sellers use discount codes to attract customers because typically, at the end of the previous year, customers have spent their money on preparing for the new year. Thus, in the first six months, there is less demand for purchasing, so discount policies are implemented to boost revenue and achieve profitability.
* August is the month with the highest revenue of the year, but discount codes are relatively low on average. This suggests that items most needed in August are in high demand, making it an optimal time to achieve the highest annual profits.
![image](https://github.com/user-attachments/assets/77052651-a48a-4403-a0fd-0df7381c8da6)
![image](https://github.com/user-attachments/assets/9781499e-46c1-4278-a2d3-e95e02714343)
![image](https://github.com/user-attachments/assets/abf59a7c-389e-4e72-8d35-5f1de2b7b56c)
- Due to the large scale of the data, the differences are not clearly visible, but they do exist in reality. Comparing the revenue of 2020 with 2021, among the stores, and among the types of products, all values are approximately the same. Could it be that the business is achieving high efficiency and consistency across different areas, or is it just a coincidence due to the data collected in 2020 and 2021, a period when the pandemic caused a similar decline in sales for all items, leading to comparable figures? Looking at the products the business sells—Clothing, Electronics, Furniture, and Toys—these items are not considered essential during the economic conditions of the pandemic, unlike Groceries. However, Groceries have revenue comparable to other items because they are not as expensive and are purchased in large quantities, leading to high revenue similar to other product categories.
![image](https://github.com/user-attachments/assets/759ecaa0-dcaa-4dad-9322-b742ecbb0e5a)
* The result is surprising: customers tend to make purchases at all hours of the day, particularly at 11 PM
* It's unusual for customers to make so many purchases at 11 PM, as this is typically a time for rest. However, this could be due to the store's locations being in different time zones, leading to discrepancies in the recorded time. The data collection might be done from a single location, which could explain why it appears that there is high activity at this hour.
![image](https://github.com/user-attachments/assets/235d49a7-e41d-40ae-bfd1-8ce5470fa9c6)
![image](https://github.com/user-attachments/assets/feaaadf9-04cf-447b-9f54-682ca23f54ac)
![image](https://github.com/user-attachments/assets/8fa00e85-8f07-4d0c-88a0-ebe02cc2ed0a)
![image](https://github.com/user-attachments/assets/b171272c-3655-4997-a652-9ee8d83fa236)
3. Customer Information
  - customer_id: Unique identifier for each customer.
  - age: Age of the customer.
  - gender: Gender of the customer (e.g., Male, Female, Other).
  - income_bracket: Income bracket of the customer (e.g., Low, Medium, High).
  - loyalty_program: Whether the customer is part of a loyalty program (Yes/No).
  - membership_years: Number of years the customer has been a member.
  - churned: Whether the customer has churned (Yes/No) - Target for classification.
  - marital_status: Marital status of the customer.
  - number_of_children: Number of children the customer has.
  - education_level: Education level of the customer (e.g., High School, Bachelor's, Master's).
  - occupation: Occupation of the customer.
  ![image](https://github.com/user-attachments/assets/69b33a5e-f1f1-43ef-986f-a34f5c570ed3)
  ![image](https://github.com/user-attachments/assets/e19c1700-c64e-4e9f-be7a-98ec1661036a)
  ![image](https://github.com/user-attachments/assets/0e40187d-8165-4a67-a627-7fb3793481ca)
4. Sale Analysis
  ![image](https://github.com/user-attachments/assets/ff07d1d3-d766-42a4-a84f-9c2c193212ba)
  ![image](https://github.com/user-attachments/assets/1484a583-4c85-4cb0-85c0-0f8922e994e2)

- Test the difference in average revenue between three types of promotions using the One-Way ANOVA test, with a significance level of α = 0.05 and the number of sample is 1000 in this experiment.
* Null Hypothesis (H0): There is no difference in average revenue between the types of promotions.
* Alternative Hypothesis (H1): At least one pair of promotion types has a difference in average revenue.
* Result
  - F-Statistic: 0.26413429842074315
  - P-Value: 0.767888282251651
  -> The result is not statistically significant.
  ![image](https://github.com/user-attachments/assets/9adc3f51-86c2-4ac9-9d51-672677e36902)
- Test whether there is a significant difference in the mean values among three data groups. The significance level is 0.05.
* H0 (Null Hypothesis): There is no difference between the three groups.
* H1 (Alternative Hypothesis): There is a difference between the three groups
F-Statistic: 0.27716609909000123
P-Value: 0.7579480209758037
-> The result is not statistically significant.






