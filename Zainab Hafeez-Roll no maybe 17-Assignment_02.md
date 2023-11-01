### Assignment-02
- Change the notebook name with your name and Roll Number.
- Try this as your own, no chatgpt (it's for your learning)
- after completing the assignment, submit this book on google class room.

Declare and print a variable with the name "name" containing your name.



```python
name= "zainab"
print(name)
```

    zainab
    

Create two variables, x and y, and swap their values without using a third variable.



```python
x = 5
y = 7
x, y = y, x
print(y)
print(x)
```

    5
    7
    

Calculate the area of a rectangle with length and width stored in variables.



```python
length = 5
width = 4
area = length*width
print (area)
```

    20
    

Create a variable with a long string (multi-line) and print its length.


```python
text = """
I am Zainab.
I have completed my bachelor's degree in geology,
and I am currently pursuing my MPhil degree in GIS and RS.
My future dream is to attain another degree in renewable energy.
"""
print(text)
print(len(text))
```

    
    I am Zainab.
    I have completed my bachelor's degree in geology,
    and I am currently pursuing my MPhil degree in GIS and RS.
    My future dream is to attain another degree in renewable energy.
    
    188
    

Create a variable to store your favorite number and print it.


```python
fav_num = 7
print(fav_num)
```

    7
    

Declare and assign values to multiple variables to represent the sides of a triangle. Calculate and print its perimeter.



```python
side1 = 3
side2 = 3
side3 = 3
perimeter = (side1 + side2 + side3)
print(perimeter)
```

    9
    

Store the price of an item in one variable and the quantity in another. Calculate and print the total cost.



```python
price_of_an_item  = 20
quantity = 2
total_cost = price_of_an_item * quantity
print(total_cost)
```

    40
    

Declare a constant variable for the value of pi (π) and use it to calculate the circumference of a circle with a given radius.


```python
pi = 3.14
radius = 5
circumference = (2)*(pi)*(radius)
print(circumference)
```

    31.400000000000002
    

Calculate the sum of two numbers, a and b.


```python
a = 7
b = 4
sum = a+b
print(sum)
```

    11
    

Calculate the product of two numbers, a and b.



```python
a = 7
b = 4
product = a*b
print(product)
```

    28
    

Calculate the result of dividing a by b (with proper error handling for division by zero).



```python
a = 10
b = 0
divide = a/b
print(divide)
```


    ---------------------------------------------------------------------------

    ZeroDivisionError                         Traceback (most recent call last)

    Cell In[24], line 3
          1 a = 10
          2 b = 0
    ----> 3 divide = a/b
          4 print(divide)
    

    ZeroDivisionError: division by zero


Calculate the square of a number x.


```python
x=2
square = x * x
print (square)
```

    4
    

Calculate the remainder when a is divided by b.


```python
a = 19
b = 2
remainder = a % b
print (remainder)
```

    1
    

 Calculate the result of dividing 17 by 3 and print the quotient and remainder.


```python
a = 17
b = 3
quotient = a//b
remainder = a%b
print (quotient)
print (remainder)
```

    5
    2
    

Calculate the area of a square with a given side length.



```python
length = 2
area = length*length
print(area)
```

    4
    

Calculate the average of five numbers.



```python
number = 2,4,6,8,10
sum = 2+4+6+8+10
count = 5
average = sum / count
print(average)
```

    6.0
    

Create a variable with a boolean value and print its opposite value.



```python
boolean_value = True
opposite_value = not boolean_value
print(opposite_value)
```

    False
    

Store your birth year in a variable and calculate your age.


```python
birth_year = 1998
present_year = 2023
age = present_year - birth_year
print(age)
```

    25
    

Create a variable with an integer and convert it to a float.


```python
integer_value = 37
float_value = float(integer_value)
print(float_value)
```

    37.0
    

Create a variable with a float and convert it to an integer.


```python
float_value =  37.0987
integer_value = int(float_value)
print(integer_value)
```

    37
    

Create a variable with a string that represents an integer and convert it to an integer.


```python
string = "2"
integer = int(string)
print(integer)
```

    2
    

Create a variable with a string that represents a float and convert it to a float.



```python
string = "2.0987"
float = float(string)
print(float)
```

    2.0987
    

Create a variable with a number and convert it to a string.


```python
number = 8
string = str(number)
print(string)
```

    8
    

Calculate the absolute value of a number.




```python
num = -4
absolute_value = abs(num)
print(absolute_value)
```

    4
    

Calculate the square root of a number.



```python
import math
number = 16
square_root = math.sqrt(number)
print(square_root)
```

    4.0
    

Calculate the value of a raised to the power of b.



```python
a = 3
b = 2
result = a ** b
print(result)
```

    9
    

Round a float to the nearest integer.


```python
float = 7.92345
rounded_integer = round(float)
print(rounded_integer)
```

    8
    

Combine multiple conditions using logical operators and print the result.

### 1st Condition


```python
a = 12
b = 56
condition1 = a>1
condition2 = b>4
result = condition1 and condition2
print(result)
```

    True
    

### 2nd Condition


```python
a = 12
b = 56
condition1 = a<9
condition2 = b>90
result = condition1 or condition2
print(result)
```

    False
    

### 3rd Condition


```python
a = 9
b = 7
condition1 = a<10
condition2 = b>4
result = condition1 or condition2
print(result)
```

    True
    

Generate a random number between 1 and 100.**(challenging)**



```python
import random
random_number = random.randint(1, 100)
print(random_number)
```

    67
    
