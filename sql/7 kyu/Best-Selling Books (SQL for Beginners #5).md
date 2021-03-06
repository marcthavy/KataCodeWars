[Best-Selling Books (SQL for Beginners #5)](https://www.codewars.com/kata/best-selling-books-sql-for-beginners-number-5)

You work at a book store. It's the end of the month, and you need to find out the 5 bestselling books at your store. Use a select statement to list names, authors, and number of copies sold of the 5 books which were sold most.

**books table schema**

- name
- author
- copies_sold

>NOTE: Your solution should use pure SQL. Ruby is used within the test cases just to validate your answer.

**SQL for Beginners Series**

This kata is part of [a collection of SQL challenges](https://www.codewars.com/collections/sql-for-beginners) for beginners. You can take the rest of the challenges here:

1. [Adults only (SQL for Beginners #1)](https://www.codewars.com/kata/590a95eede09f87472000213)
2. [On the Canadian Border (SQL for Beginners #2)](https://www.codewars.com/kata/590ba881fe13cfdcc20001b4)
3. [Register for the Party (SQL for Beginners #3)](https://www.codewars.com/kata/590cc86f7557c0494000007e)
4. [Collect Tuition (SQL for Beginners #4)](https://www.codewars.com/kata/5910b0d378cc2ba91400000b)
5. [Best-Selling Books (SQL for Beginners #5)](https://www.codewars.com/kata/591127cbe8b9fb05bd00004b)
6. [Countries Capitals for Trivia Night (SQL for Beginners #6)](https://www.codewars.com/kata/5e5f09dc0a17be0023920f6f)

```sql
SELECT
  *
FROM
  books
ORDER BY
  copies_sold DESC
LIMIT 5
```