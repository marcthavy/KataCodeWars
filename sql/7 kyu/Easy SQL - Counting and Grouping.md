[Easy SQL: Counting and Grouping](https://www.codewars.com/kata/594633020a561e329a0000a2)

Given a demographics table in the following format:

**demographics table schema**

- id
- name
- birthday
- race

you need to return a table that shows a count of each race represented, ordered by the count in descending order as:

**output table schema**

- race
- count

```sql
SELECT
  race,
  count(*)
FROM
  demographics
GROUP BY
  race
ORDER BY
  count(*) DESC
```