## Numbers

Variables can also hold numeric values. The simplest kind of number in Python is the integer, which is a whole number with no decimal point:

```python
int1 = 1
int2 = 10
int3 = -5
```

A number with a decimal point is called a float. You can define floats with numbers after the decimal point or by just including a decimal point at the end:

``` python
float1 = 1.0
float2 = 10.
float3 = -5.5
```

You can also define a float using scientific notation, with e indicating the power of 10:

``` python
# this evaluates to 150:
float4 = 1.5e2
```

## Code Example
Instructions  | 
------------  | 
1.You are going shopping. Let's make a grocery list so that you can plan your budget. Store the number of cucumbers you want to buy in a variable called cucumbers. Make sure it's at least 1, and that it's the appropriate datatype! The store doesn't sell partial cucumbers.
2.Each cucumber costs 3.25 doubloons. Store the price per cucumber in a variable called price_per_cucumber.
3.Create a new variable called total_cost which is the product of how many cucumbers you are going to buy and the cost per cucumber.
4.Print out total_cost. What datatype is it? 

``` python
cucumbers = 1 

price_per_cucumber = float(3.25)

total_cost = cucumbers * price_per_cucumber

print total_cost
```
