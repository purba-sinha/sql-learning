# SQL Learning Journey

Documenting my daily SQL practice as I learn.
Currently working through SQLZoo.

## 🛠️ Topics Covered So Far

* ☑ **SELECT Basics**: Core syntax for retrieving data from tables.
* ☑ **Filtering Data**: `WHERE`, `BETWEEN`, `LIKE`, `IN`, `OR`, `XOR`.
* ☑ **Pattern Matching / Wildcards**: Searching for specific string patterns using `%` with the `LIKE` operator.
* ☑ **Data Formatting & Manipulation**: `ROUND()`, `LENGTH()`, `LEFT()` functions.
* ☑ **Query Modifiers**: `AS` (Aliasing), `DISTINCT`, `ORDER BY` (ASC/DESC).
* ☑ **Data Grouping & Row Filtering**: `GROUP BY` and the `HAVING` clause.
* ☑ **Aggregate Functions**: `SUM()`, `COUNT()`, `AVG()`, `MIN()`, `MAX()`.
* ☑ **Subqueries**: Nested queries (`SELECT` within `SELECT`) and using the `ALL` keyword.
* ☑ **Correlated Subqueries**: Advanced row-by-row comparisons using multiple table aliases (e.g., `c1`, `c2`) for the same table.


## Currently Learning
- JOIN operations

## Resources
- SQLZoo
- HackerRank SQL
## Day 3 - Revision
- Revised all topics covered so far
- SELECT, WHERE, GROUP BY, Subqueries, 
  Correlated Subqueries, ORDER BY, DISTINCT

## Day 4 - Aggregations & Correlated Subqueries

* Learned how to use `MAX()` and `MIN()` to find extreme values in a dataset.
* Mastered the `HAVING` clause to filter grouped data where `WHERE` can't be used.
* Practiced advanced Correlated Subqueries by aliasing the same table (`c1`, `c2`) to perform row-by-row population comparisons within the same continent.

☑ SUM, COUNT, AVG functions
☑ Pattern Matching / Wildcards (`%`)

## Day 5 - Aggregate Functions & Wildcard Searching

* **Quizzes Completed**: Knocked out 2 SQL quizzes to test my understanding of foundational concepts and subqueries.
* **Basic Aggregations**: Mastered how to use `SUM()`, `COUNT()`, and `AVG()` to calculate totals, tallies, and averages across datasets.
* **Wildcard Filtering (`%`)**: Learned how to use the `LIKE` operator with the `%` wildcard to search for flexible text patterns:
  * `LIKE 'A%'` – Finds values starting with "A".
  * `LIKE '%a'` – Finds values ending with "a".
  * `LIKE '%a%'` – Finds values containing "a" anywhere in the string.

☑ JOIN operations & the `ON` clause

## ⏳ Currently Learning
* Types of JOINs (LEFT, RIGHT, FULL OUTER)
* Database normalization and primary/foreign keys

## Day 6 - Relational Databases & JOIN Operations

* **The Power of Relational Data**: Learned why databases split data into multiple tables to avoid duplication, and how `JOIN` links them back together.
* **The `JOIN` Syntax**: Mastered combining rows from two or more tables based on a related column between them.
* **The `ON` Clause**: Learned how to specify the exact matching condition (usually linking a Primary Key to a Foreign Key) to stitch the tables together properly.
  * *Example structure:* `FROM TableA JOIN TableB ON TableA.id = TableB.a_id`

## Day 7 - Revision & Consolidation

* **Focus**: Paused new topics to solidify concepts from the past week.
* **Review Scope**: Re-practiced writing queries using basic filters (`LIKE`, `%`), aggregations, and nested subqueries.

### Day 8: Joins, Nulls & Numeric Operations

* **Joins:** Mastered `INNER`, `LEFT`, `RIGHT`, and `FULL` joins to merge relational tables.
* **Null Handling:** Used `IS NULL` / `IS NOT NULL` and `COALESCE()` to handle missing data.
* **Numeric Functions:** Applied mathematical operations and rounding to format raw data.
* 
* # Day 9
  
- Numeric functions help manipulate and format numbers.
- Window functions perform calculations across rows without collapsing the result set.
- Difference between RANK() and DENSE_RANK().
- Running totals using SUM() OVER().

# Day 10
Learned aggregate functions — COUNT, SUM, AVG, MIN, MAX — along with GROUP BY and HAVING to filter grouped results. 

# Day 11
Covered all types of joins — INNER, LEFT, RIGHT, FULL OUTER, and self joins — plus subqueries (nested and correlated) for multi-step queries.

# Day 12
covered about subqueries, correlated subqueries, nested queries, common table expressions CTEs
 # Day 13
 [Brazilian E-Commerce Public Dataset by Olist] - SQL Practice
 **Source:** [https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce]

 **Concepts practiced:**
 - [JOINS (INNER, LEFT)]
 - [Subqueries / Window functions]
 
# Day 14
today's focus was on SQL JOIN operations. Practiced writing queries using INNER JOIN, Left JOIN, RIGHT JOIN, and FULL OUTER JOIN to retrieve and combine data from multiple related tables. Completed several practice problems to stengthen understanding of relational database concepts.

# Day 15
- Retrieved data from multiple related tables.

- Understood how different JOINs affect query results.

- Improved SQL query writing and debugging.

  # Day 16
- learned about Self join, Cross Join, Subqueries, Common table expressions, Window functions

  # Day 17
- practiced same concepts on a kaggle dataset

  # Day 18
- practiced ROW_NUMBER(), RANK(), DENSE_RANK(), NTITLE(), LAG(), LEAD(), Moving averages on a kaggle dataset
