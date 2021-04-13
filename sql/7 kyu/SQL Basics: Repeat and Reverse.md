[SQL Basics: Repeat and Reverse](https://www.codewars.com/kata/59414360f5c3947364000070/)

Using our monsters table with the following schema:

**monsters table schema**

- id
- name
- legs
- arms
- characteristics
- return the following table:

**output schema**

- name
- characteristics

Where the name is the original string repeated three times (do not add any spaces), and the characteristics are the original strings in reverse (e.g. 'abc, def, ghi' becomes 'ihg ,fed ,cba').

```sql
SELECT
  repeat(name,3) "name",
  reverse(characteristics) "characteristics"
FROM
  monsters
```
