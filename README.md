# danny_pizza_runner
This is the week Two of the 8 Week SQL Challenge by Danny Ma.[Click here to view all material and respected credit](https://8weeksqlchallenge.com/case-study-2/)
![image](https://8weeksqlchallenge.com/images/case-study-designs/2.png)
# Introduction
Did you know that over 115 million kilograms of pizza is consumed daily worldwide??? (Well according to Wikipedia anyway…)

Danny was scrolling through his Instagram feed when something really caught his eye - “80s Retro Styling and Pizza Is The Future!”

Danny was sold on the idea, but he knew that pizza alone was not going to help him get seed funding to expand his new Pizza Empire - so he had one more genius idea to combine with it - he was going to Uberize it - and so Pizza Runner was launched!

Danny started by recruiting “runners” to deliver fresh pizza from Pizza Runner Headquarters (otherwise known as Danny’s house) and also maxed out his credit card to pay freelance developers to build a mobile app to accept orders from customers.

# Available Data
Because Danny had a few years of experience as a data scientist - he was very aware that data collection was going to be critical for his business’ growth.

He has prepared for us an entity relationship diagram of his database design but requires further assistance to clean his data and apply some basic calculations so he can better direct his runners and optimise Pizza Runner’s operations.
# Entity Relationship Diagram
![image](https://miro.medium.com/v2/resize:fit:1400/1*Ry0ZnSd4Swh2mcm1IH7NFQ.png)

# Skill Demostrated
- Data Cleaning in SQL.
- SQL Querying.
- Data Manipulation.
- Problem-Solving.
- Database Schema Understanding.
# Case Study
-  [Data Cleaning](https://github.com/LeoDSaint/danny_pizza_runner/blob/main/data_cleaning_pizza_runner).
-  [Part A. Pizza Metrics](https://github.com/LeoDSaint/danny_pizza_runner/blob/main/A_Pizza_Metrics).
-  [Part B. Runner and Customer Experience](https://github.com/LeoDSaint/danny_pizza_runner/blob/main/B_Runner_and_Customer_Experience).
-  [Part C. Ingredient Optimisation](https://github.com/LeoDSaint/danny_pizza_runner/blob/main/C_Ingredient_Optimization)



# Insight
1. Total of 14 orders were placed. These orders originated from 10 distinct customers.
2. Runner 1 has the highest number of successful deliveries, with a total of 4 deliveries. This indicates that Runner 1 
   has been the most active and efficient in completing successful deliveries among all 3 runners in the dataset.
3. A total of 9 MeatLovers pizzas were delivered, while 3 Vegetarian pizzas were delivered. This showcases a higher
   demand for the Meat Lover pizza compared to the Vegetarian option
4. only one delivered pizza had both extra toppings and exclusions specified. This suggests that most customers either 
   opted for additional toppings or requested certain ingredients to be excluded, but not both simultaneously. It could 
   be inferred that customers typically choose one customization option over the other, rather than combining them in a 
   single order.
5. Most orders were made Saturdays and Wednesdays. The least order was on Fridays
6. Week one has the highest number of runner sign-ups, with a total of 2 runners joining the platform. 
7. There is a positive relationship between avg delivery time and pizza quantity. This implies that as
   the number of pizzas in an order increases, the average delivery time also tends to increase.
8. Customer 105 has the highest average distance traveled compared to other customers. This indicates that, 
   on average, Customer 105's delivery locations are situated farther away from the pizza store compared to
   the average distances traveled by other customers.
9. Runner 2 is the fastest rider
10. Runner 1 has the highest delivery rate
11. Bacon is the most commonly added extra while Cheese is the most common exclusion
12. Mushrooms & Bacon are the most used Ingredient
13. The restaurant generated a total revenue of $138.
14. Pizza runner has a total of $94.44 after payment has been made to riders

# Recommendation 
1. Optimize delivery routes: Since there is a positive relationship between the average delivery time and pizza quantity,
   it is essential to optimize delivery routes to minimize delivery times. Implementing efficient route planning can help
   reduce overall delivery times.

2. Offer promotions on Fridays: As the data indicates that Fridays have the lowest number of orders, consider offering 
   promotions or discounts specifically targeted for Fridays to incentivize customers and boost order volumes on that day.

3. Analyze customer preferences: Further analyze customer preferences for Meat Lover and Vegetarian pizzas to understand 
   the demand patterns better. This can help in adjusting the inventory and ingredients accordingly to meet customer 
   expectations and maximize customer satisfaction.

4. Provide incentives for runners: Acknowledge and reward the top-performing runner, such as Runner 1, who has the highest
   number of successful deliveries. This can help motivate and retain efficient runners while encouraging healthy 
   competition among the delivery team.

5. Explore marketing opportunities: Given that most orders occur on Saturdays and Wednesdays, consider allocating marketing
   efforts and resources towards these peak days. This can involve targeted advertising campaigns, promotions, or 
   partnerships to further drive customer engagement and increase order volumes.



