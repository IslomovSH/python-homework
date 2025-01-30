**Homework Assignment 1: Analyzing Sales Data**

You are given a dataset containing sales data for an e-commerce website. The dataset (`task\sales_data.csv`) has the following columns:

- `Date`: Date of the sale.
- `Product`: Name of the product sold.
- `Category`: Category to which the product belongs.
- `Quantity`: Number of units sold.
- `Price`: Price per unit.

**Tasks:**

1. Group the data by the `Category` column and calculate the following aggregate statistics for each category:
   - Total quantity sold.
   - Average price per unit.
   - Maximum quantity sold in a single transaction.
2. Identify the top-selling product in each category based on the total quantity sold.
3. Find the date on which the highest total sales (quantity * price) occurred.

**Homework Assignment 2: Examining Customer Orders**

You have a dataset (`task\customer_orders.csv`) containing information about customer orders. The dataset has the following columns:

- `OrderID`: Unique identifier for each order.
- `CustomerID`: Unique identifier for each customer.
- `Product`: Name of the product ordered.
- `Quantity`: Number of units ordered.
- `Price`: Price per unit.

**Tasks:**

1. Group the data by `CustomerID` and filter out customers who have made less than 20 orders.
2. Identify customers who have ordered products with an average price per unit greater than $120.
3. Find the total quantity and total price for each product ordered, and filter out products that have a total quantity less than 5 units.

**Homework Assignment 3: Population Salary Analysis**

1. "task\population.db" sqlite database has `population` table.
2. "task\population salary analysis.xlsx" file defines Salary Band categories. <br />
    Read the data from population table and calculate following measures:
    - Percentage of population for each salary category;
    - Average salary in each salary category;
    - Median salary in each salary category;
    - Number of population in each salary category;
3. Calculate the same measures in each State

Note: Use SQL only to select data from database. All the other calculations should be done in python.




