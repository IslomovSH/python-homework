# Homeworks

## 1. Modify String with Underscores
Given a string `txt`, insert an underscore (`_`) after every third character. If a character is a vowel or already has an underscore after it, shift the underscore placement to the next character. No underscore should be added at the end.

### Examples
**Input:** `hello`
**Output:** `hel_lo`

**Input:** `assalom`
**Output:** `ass_alom`

**Input:** `abcabcabcdeabcdefabcdefg`
**Output:** `abc_abcab_cdeabcd_efabcdef_g`

---

## 2. Integer Squares Exercise

### Task
The provided code stub reads an integer, `n`, from STDIN. For all non-negative integers `i` where `0 <= i < n`, print `i^2`.

### Example Input
```
5
```

### Example Output
```
0
1
4
9
16
```

### Input Format
The first and only line contains the integer, `n`.

### Constraints
- `1 <= n <= 20`

### Output Format
Print `n` lines, one corresponding to each `i^2` where `0 <= i < n`.

---

## 3. Loop-Based Exercises

### Exercise 1: Print first 10 natural numbers using a while loop

### Exercise 2: Print the following pattern
```
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
```

### Exercise 3: Calculate sum of all numbers from 1 to a given number
**Example:**
```
Enter number 10
Sum is: 55
```

### Exercise 4: Print multiplication table of a given number
**Example:**
```
2
4
6
8
10
12
14
16
18
20
```

### Exercise 5: Display numbers from a list using a loop
**Given:**
```python
numbers = [12, 75, 150, 180, 145, 525, 50]
```
**Expected Output:**
```
75
150
145
```

### Exercise 6: Count the total number of digits in a number
**Example:**
```
75869
Output: 5
```

### Exercise 7: Print reverse number pattern
```
5 4 3 2 1
4 3 2 1
3 2 1
2 1
1
```

### Exercise 8: Print list in reverse order using a loop
**Given:**
```python
list1 = [10, 20, 30, 40, 50]
```
**Expected Output:**
```
50
40
30
20
10
```

### Exercise 9: Display numbers from -10 to -1 using a for loop
```
-10
-9
-8
-7
-6
-5
-4
-3
-2
-1
```

### Exercise 10: Display message “Done” after successful loop execution
**Example:**
```python
0
1
2
3
4
Done!
```

### Exercise 11: Print all prime numbers within a range
**Example:**
```
Prime numbers between 25 and 50:
29
31
37
41
43
47
```

### Exercise 12: Display Fibonacci series up to 10 terms
**Example:**
```
Fibonacci sequence:
0  1  1  2  3  5  8  13  21  34
```

### Exercise 13: Find the factorial of a given number
**Example:**
```
5! = 120
```

---

## 4. Return Uncommon Elements of Lists
### Task
Return the elements that are not common between two lists. The order of elements does not matter.

### Examples
- **Input:** `list1 = [1, 1, 2], list2 = [2, 3, 4]`  
  **Output:** `[1, 1, 3, 4]`

- **Input:** `list1 = [1, 2, 3], list2 = [4, 5, 6]`  
  **Output:** `[1, 2, 3, 4, 5, 6]`

- **Input:** `list1 = [1, 1, 2, 3, 4, 2], list2 = [1, 3, 4, 5]`  
  **Output:** `[2, 2, 5]`

