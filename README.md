# CEB1250_repo
### Articles Reaction - See attached document for Articles

### Coding Exercises & other tasks:
#### Session 1: PYTHON 101

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
#### Session 2: SQL
###### 1. Please see excel document for 3rd Normal Form exercise.
```python

 2.Return all salaries that are between 40000 and 60000

 mysql> select salary from employees.salaries where salary>=40000 and salary<=60000;
    Answer: 1336403 rows in set (1.90 sec)

```

