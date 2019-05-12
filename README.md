# CEB1250_repo
### Articles Reaction - See attached document for Articles

### Coding Exercises & other tasks:

#### Class 1: PYTHON 101

hello world
##### 1. Give me a number to square.
```python
def showSquare():
    number = int(input("Please write a number: "))
    
    print(number*number)

showSquare()
```
##### 2. Convert degrees of Fahrenheit to Celsius.
```python
def weather():
    temperature = int(input("Please write Fahrenheit temperature to convert to Celsius: "))
    
    print((temperature-32)*5/9)
    
weather()
```
##### 3. Are we Even or that's Odd?.
```python
def showOddOrEven():
    number = int(input("Are we Even or that's Odd? Please enter a number: "))
    if (number % 2 == 0):
        print("Fine we're Even!")
    else:
        print("Well, that's Odd!")
    
showOddOrEven()
```
##### 4. The largest number in the list.
```python
def largest_num_in_the_list( list ):
    max = list[ 0 ]
    for a in list:
        if a > max:
            max = a
    return max
print(largest_num_in_the_list([1, 10, -8, 0, 3, 17, 5]))
```
##### 5. Palindrome Check.
```python
def itIsPalindrome():
    mystring = input("Check a word if it is a Palindrome. Enter a word: ")
    for i in range(len(mystring) // 2):
        if mystring[i] != mystring[- 1 - i]:
            print('It is not Palindrome. Oopsie..')
        else:
            print('It is a Palindrome. Yay!')
            
itIsPalindrome()
```
##### 6. Count the number of vowels.
```python
def vowelCounter(listCountry):
    string = ''.join(listCountry)
    count = 0
    vowels = 'aeiouAEIOU'
    for ch in string:
        if ch in vowels:
            count += 1
    return count

print(vowelCounter(["usa","canada","thailand","philippines"]))
```
#### Class 2: SQL
```python

 1. Please see excel document for 3rd Normal Form exercise.

 2. Return all salaries that are between 40000 and 60000

mysql> select salary from employees.salaries where salary>=40000 and salary<=60000;

    Answer: 1336403 rows in set (1.90 sec)

 3.Get all employees hired after 01-01-1995

mysql> select distinct hire_date from employees.employees where hire_date>1995-01-01

    Answer: 5434 rows in set, 1 warning (0.24 sec)

4. Get all salaries from 60000 to 90000

mysql> select salary from employees.salaries where salary>=60000 and salary<=90000

    Answer: 1261748 rows in set (1.01 sec)

5. Get all titles where title is equal to engineer

mysql> select title from employees.titles where title='Engineer'

    Answer: 115003 rows in set (0.22 sec)

```

### Class 3: SQL-Relational Database Nested Queries

```python

1.  Return the minimum salary of the salary table

mysql> select salary from employees.salaries order by salary asc limit 10

Answer: 38623

2. What is the difference between “Having” and “Where” clauses

Answer: A WHERE clause is used is filter records from a result.  The filter occurs before any groupings are made.
        A HAVING clause is used to filter values from a group.

3. Return the maximum value for date of birth on the employee table

Answer: 1965-02-01

```

### Class 4:

```python

ACID & BASE

1. Define a scenario where ACID properties are needed, enlist 3 reasons why.

Booking a flight ticket, or buying tickets for a show. 
Because ACID has zero tolerance for error, consistent, and where transaction requires minimal speed.

2. Define a scenario where BASE properties are needed, enlist 3 reasons why.

NoSQL Types

1. Your client wants to find potential clients based on their locations or interests, what would you suggest? 

Answer: Graph

2. You need to store the logs from your billing system in a way that they will become easy to access.

Answer: Document

3. You want to analyze the most accessed site of your e-commerce platform over the time. Where would you store the data?

Answer: Columnar

4. You want to store the inventory of your website contents per endpoints. The page contents will be labelled with the page endpoint accessed, for quick access. Which database solution you would choose?

Answer: Relational Database

5. You have to store financial information about your clients, such as balance account and personal information. Which one you will use?

Answer: Relational Database

```





