[SQL Basics: Maths with String Manipulations](https://www.codewars.com/kata/sql-basics-maths-with-string-manipulations)

Given a demographics table in the following format:

**demographics table schema**

- id
- name
- birthday
- race

return a single column named 'calculation' where the value is the bit length of name, added to the number of characters in race.

```sql
SELECT
  bit_length(name) + length(race) calculation
FROM
  demographics
```
