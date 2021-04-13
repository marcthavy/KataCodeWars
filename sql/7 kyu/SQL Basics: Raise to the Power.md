[SQL Basics: Raise to the Power](https://www.codewars.com/kata/sql-basics-raise-to-the-power)

Given the following table 'decimals':

**decimals table schema**

- id
- number1
- number2

Return a table with one column (result) which is the output of number1 raised to the power of number2.

```sql
SELECT
  power(number1, number2) result
FROM
  decimals
```
