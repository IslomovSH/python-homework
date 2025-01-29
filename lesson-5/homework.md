Homework:
1. <a href="https://www.hackerrank.com/challenges/write-a-function/problem">Find leap year</a>

for this puzzle don't create function.

answer 1:

```python
year = int(input("Enter a year: "))

if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
    print(f"{year} is a leap year.")
else:
    print(f"{year} is not a leap year.")
```

answer 2:
```python
year = int(input("Enter a year: "))

if year % 4 == 0:
    if year % 100 == 0:
        if year % 400 == 0:
            print(f"{year} is a leap year.")
        else:
            print(f"{year} is not a leap year.")
    else:
        print(f"{year} is a leap year.")
else:
    print(f"{year} is not a leap year.")
```

2. <a href="https://www.hackerrank.com/challenges/py-if-else/problem">if-else problem</a>

3. Given two integer numbers a and b. Find even numbers between this numbers. a and b are inclusive. Don't use loop. 

Give two solutions.

Solution 1 with if-else statement.

Solution 2 without if-else statement.
