# Python Exercises - Print & Arithmetic

This repository contains a set of Python programming exercises focused on basic printing and arithmetic operations. These exercises are designed to help improve coding skills by practicing fundamental concepts.

## Exercises

### Exercise 1: Display a Number

**Statement:** Write a Python program that prints the number `15` to the standard output.

**Solution:**

```python
print(15)
```

### Exercise 2: Calculate the Number of Months, Weeks, and Days in 27 Years

**Statement:**

1. Declare a variable `nb_years` with the value `27`.
2. Compute the total number of months (`nb_months`), days (`nb_days`), and weeks (`nb_weeks`) for this duration.
3. Display the results in the format:

   `In 27 years, there are X months, about Y weeks, and Z days.`

**Solution:**

```python
nb_years = 27
nb_months = nb_years * 12
nb_days = nb_years * 365
nb_weeks = nb_days // 7

print(
    f'In 27 years, there are {nb_months} months, about {nb_weeks} weeks, and {nb_days} days.'
)
```

### Exercise 3: Calculate the Area of a Circle

**Statement:**

1. Declare a variable `radius` with the value `5`.
2. Use the constant `pi` from the `math` module to calculate the area of a circle with this radius.
3. Display the result in the format:

   `The area of a circle with a radius of 5 is X.`

**Solution:**

```python
from math import pi

radius = 5
area = (pi * radius)**2

print(f'The area of a circle with a radius of {radius} is {area}.')
```

