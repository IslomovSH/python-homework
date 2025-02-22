Homework 1:

import pandas as pd

data = {'First Name': ['Alice', 'Bob', 'Charlie', 'David'],
        'Age': [25, 30, 35, 40],
        'City': ['New York', 'San Francisco', 'Los Angeles', 'Chicago']}
df = pd.DataFrame(data)

1. Rename column names using function. "First Name" --> "first_name", "Age" --> "age
2. Print the first 3 rows of the DataFrame
3. Find the mean age of the individuals
4. Select and print only the 'Name' and 'City' columns
5. Add a new column 'Salary' with random salary values
6. Display summary statistics of the DataFrame

Homework 2:

1. Create a DataFrame named sales_and_expenses with columns 'Month', 'Sales', and 'Expenses', representing monthly sales and expenses data.
Use below table.

| Month | Sales | Expenses |
|-------|-------|----------|
| Jan   | 5000  | 3000     |
| Feb   | 6000  | 3500     |
| Mar   | 7500  | 4000     |
| Apr   | 8000  | 4500     |


2. Calculate and display the maximum sales and expenses.
3. Calculate and display the minimum sales and expenses.
4. Calculate and display the average sales and expenses.


Homework 3:

1. Create a DataFrame named expenses with columns 'Category', 'January', 'February', 'March', and 'April', representing monthly expenses for different categories. Use below table.

| Category       | January | February | March | April |
|----------------|---------|----------|-------|-------|
| Rent           | 1200    | 1300     | 1400  | 1500  |
| Utilities      | 200     | 220      | 240   | 250   |
| Groceries      | 300     | 320      | 330   | 350   |
| Entertainment  | 150     | 160      | 170   | 180   |


2. Calculate and display the maximum expense for each category.
3. Calculate and display the minimum expense for each category.
4. Calculate and display the average expense for each category.

In this task, use `.set_index` method to make Category column as index. 

Try this code, learn it and use it in the task.

> expenses.set_index('Category')



