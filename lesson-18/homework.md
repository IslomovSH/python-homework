Homework 2:
```
df = pd.read_csv('task\\stackoverflow_qa.csv')
df.head()
```
| id       | creationdate       | score | viewcount | title                                         | answercount | commentcount | favoritecount | quest_name       | quest_rep | ans_name         | ans_rep  |
|----------|--------------------|-------|-----------|-----------------------------------------------|-------------|--------------|---------------|------------------|-----------|------------------|----------|
| 332289   | 2008-12-01 21:24:44 | 3184  | 5962784   | How do I change the size of figures drawn with... | 14          | 1            | 0.0           | tatwright        | 37837.0   | NaN              | NaN      |
| 2051744  | 2010-01-12 19:31:47 | 420   | 587728    | How to invert the x or y axis                 | 10          | 3            | 0.0           | DarkAnt          | 4211.0    | Demitri          | 13369.0  |
| 2225995  | 2010-02-09 00:51:38 | 51    | 59922     | How can I create stacked line graph?          | 4           | 0            | 0.0           | David Underhill  | 15936.0   | doug             | 69290.0  |
| 5486226  | 2011-03-30 12:26:50 | 7     | 6393      | Rolling median in python                      | 5           | 4            | 0.0           | yueerhu          | 175.0     | Mike Pennington  | 42288.0  |
| 5515021  | 2011-04-01 14:50:44 | 10    | 13744     | Compute a compounded return series in Python  | 3           | 6            | 0.0           | Jason Strimpel   | 14916.0   | Mike Pennington  | 42288.0  |

1. Find all questions that were created before 2014
2. Find all questions with a score more than 50
3. Find all questions with a score between 50 and 100
4. Find all questions answered by Scott Boston
5. Find all questions answered by the following 5 users
6. Find all questions that were created between March, 2014 and October 2014 that were answered by Unutbu and have score less than 5.
7. Find all questions that have score between 5 and 10 or have a view count of greater than 10,000
8. Find all questions that are not answered by Scott Boston


Homework 3:

Titanic data set, stored as CSV. The data consists of the following data columns:

- PassengerId: Id of every passenger.
- Survived: Indication whether passenger survived. 0 for yes and 1 for no.
- Pclass: One out of the 3 ticket classes: Class 1, Class 2 and Class 3.
- Name: Name of passenger.
- Sex: Gender of passenger.
- Age: Age of passenger in years.
- SibSp: Number of siblings or spouses aboard.
- Parch: Number of parents or children aboard.
- Ticket: Ticket number of passenger.
- Fare: Indicating the fare.
- Cabin: Cabin number of passenger.
- Embarked: Port of embarkation.

```
titanic_df = pd.read_csv("task\\titanic.csv")
titanic_df.head()
```

| PassengerId | Survived | Pclass | Name                                             | Sex    | Age   | SibSp | Parch | Ticket           | Fare    | Cabin | Embarked |
|-------------|----------|--------|--------------------------------------------------|--------|-------|-------|-------|------------------|---------|-------|----------|
| 1           | 0        | 3      | Braund, Mr. Owen Harris                         | male   | 22.0  | 1     | 0     | A/5 21171        | 7.2500  | NaN   | S        |
| 2           | 1        | 1      | Cumings, Mrs. John Bradley (Florence Briggs Th.) | female | 38.0  | 1     | 0     | PC 17599         | 71.2833 | C85   | C        |
| 3           | 1        | 3      | Heikkinen, Miss. Laina                          | female | 26.0  | 0     | 0     | STON/O2. 3101282 | 7.9250  | NaN   | S        |
| 4           | 1        | 1      | Futrelle, Mrs. Jacques Heath (Lily May Peel)    | female | 35.0  | 1     | 0     | 113803           | 53.1000 | C123  | S        |
| 5           | 0        | 3      | Allen, Mr. William Henry                        | male   | 35.0  | 0     | 0     | 373450           | 8.0500  | NaN   | S        |


1. Select Female Passengers in Class 1 with Ages between 20 and 30:
Extract a DataFrame containing female passengers in Class 1 with ages between 20 and 30.

2. Filter Passengers Who Paid More than $100:
Create a DataFrame with passengers who paid a fare greater than $100.

3. Select Passengers Who Survived and Were Alone:
Filter passengers who survived and were traveling alone (no siblings, spouses, parents, or children).

4. Filter Passengers Embarked from 'C' and Paid More Than $50:
Create a DataFrame with passengers who embarked from 'C' and paid more than $50.

5. Select Passengers with Siblings or Spouses and Parents or Children:
Extract passengers who had both siblings or spouses aboard and parents or children aboard.

6. Filter Passengers Aged 15 or Younger Who Didn't Survive:
Create a DataFrame with passengers aged 15 or younger who did not survive.

7. Select Passengers with Cabins and Fare Greater Than $200:
Extract passengers with known cabin numbers and a fare greater than $200.

8. Filter Passengers with Odd-Numbered Passenger IDs:
Create a DataFrame with passengers whose PassengerId is an odd number.

9. Select Passengers with Unique Ticket Numbers:
Extract a DataFrame with passengers having unique ticket numbers.

10. Filter Passengers with 'Miss' in Their Name and Were in Class 1:
Create a DataFrame with female passengers having 'Miss' in their name and were in Class 1.



