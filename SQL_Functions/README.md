# SQL Functions

## What is SQL Functions?

- Functions in SQL are prewritten actions that accept an input value/s, processes it and returns an ouput value.

- SQL functions are pre-written actions that can manipulate data, perform calculations, and return results. Common SQL functions include COUNT, SUM, AVG, and ROUND.

  Input Value/s -> **FUNCTIONS** -> Output Value/s


## SQL Function Categories

**1. Singe-Row Functions:** We give only one value and function returns to us a single value

*e.g. 'ANNA' -> **LOWER()** -> 'anna'*


**2. Mutli-Row Functions:** We give more than one value and then the function returns one single value

*e.g. 30, 10, 20, 40 -> **SUM()** -> 100*


## NESTED FUNCTIONS

- Function used inside another function

*e.g. 'Maria' -> **LEFT(2)** -> 'Ma' -> **LOWER()** -> 'ma'*

*function in SQL query: LOWER(LEFT('Maria', 2))*
