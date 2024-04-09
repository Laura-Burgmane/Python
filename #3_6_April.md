# Python
## Conditional execution |


- Python reserved words
- Indentation
- Comparison operations
- Two-way decisions with if and else
- __Team work:__ Create a Python program for temperature conversion between Celsius and Fahrenheit scales. The program should prompt users to select the direction of conversion, accept input for the temperature value, and accurately perform the conversion (use IF and/or ELSE). Output should be displayed with formatted strings showing both the original and converted temperatures.


## Teamwork code:

```py
which_temp = input('Do you want to enter temperature in Celsius (yes/no)?')

if which_temp == 'yes': 
  tempC = float(input('Insert the temperature in Celsius: '))
  tempF = float((9/5 * tempC) + 32)
  print(f"Temperature {tempC} equals to {tempF} in Fahrenheit")
else:
  tempF = float(input('Insert the temperature in Fahrenheit: '))
  tempC = float((tempF - 32) * 5/9)
  print(f"Temperature {tempF} equals to {tempC} in Celsius")
```
