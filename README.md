**PIZZA-SALES-ANALYSIS-USING-SQL**
From total revenue generated from pizza sales to top 3 most ordered pizza types based on revenue for each pizza category, there are 20 different queries are executed to Analyze the Sales data of Pizza Company.

**Key Highlights:**

I have used 4 different tables and from basic to advanced queries to retrieve these all queries -->

pizzas table(containing 4 columns)-->pizza_id, pizza_type_id, size and price.
pizza_types table(containing 4 columns)--> pizza_type_id,name,category and ingredients.
orders table(containing 3 columns)-->order_id,order_date and order_time.
4.order_details table(containing 4 columns)-->order_details_id,order_id,pizza_id and quantity.

I have used COUNT(),SUM(),RANK(),OVER(),GROUP BY(),ORDER BY(),LIMIT and others clauses in these 20 questions.

The 20 different queries are: SQL PROJECT QUESTIONS:

Retrieve the total number of orders placed
Retrieve distinct pizza type ordered
Retrieve number of pizza ordered where pizza_size='xxl' and it's pizza_id
Calculate the total revenue generated from pizza sales--> Rounded upto 2 decimal places
Wants to know the pizza types where special ingredients-->'Mushrooms' and 'Pepperoni' used
Need to find the number of pizzas in different categroies
Identify the highest-priced pizza
Identify the highest-priced pizza and Revenue generated from it
Identify the most common pizza size ordered
List the top 5 most ordered pizza types along with their quantities.
Join the necessary tables to find the total quantity of each pizza category ordered
Determine the distribution of orders by hour of the day.
Determine the top 5 distribution of orders by hour of the day
Group the orders by date and calculate the average number of pizzas ordered per day
Group the orders by date and calculate the top 10 day when maximum pizza ordered
Find the total pizza ordered and revenue generated month wise and revenue earned >70000
Determine the top 5 most ordered pizza types based on revenue
Calculate the percentage contribution of each pizza type to total revenue
Analyze the cumulative revenue generated over time
Determine the top 3 most ordered pizza types based on revenue for each pizza category
