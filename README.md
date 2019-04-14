# CEB1250_repo
hello world
### 1. Give me a number to square.
```python
def showSquare():
    number = int(input("Please write a number: "))
    
    print(number*number)

showSquare()
```
### 2. Convert degrees of Fahrenheit to Celsius.
```python
def weather():
    temperature = int(input("Please write Fahrenheit temperature to convert to Celsius: "))
    
    print((temperature-32)*5/9)
    
weather()

```
### 3. Are we Even or that's Odd?.
```python
def showOddOrEven():
    number = int(input("Are we Even or that's Odd? Please enter a number: "))
    if (number % 2 == 0):
        print("Fine we're Even!")
    else:
        print("Well, that's Odd!")
    
showOddOrEven()