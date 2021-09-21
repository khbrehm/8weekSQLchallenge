Case Study #1 - Dannys Diner

/* 
https://www.db-fiddle.com/f/2rM8RAnq7h5LLDTzZiRWcd/138
*/

-- 1. What is the total amount each customer spent at the restaurant?

    SELECT s.customer_id, SUM(price) AS total_sales
    FROM dannys_diner.sales AS s
    JOIN dannys_diner.menu AS m
       ON s.product_id = m.product_id
    GROUP BY customer_id
    ORDER BY customer_id;

| customer_id | total_sales |
| ----------- | ----------- |
| A           | 76          |
| B           | 74          |
| C           | 36          |

---
ANSWER
Customer A spent $76
Customer B spent $74
Customer C spent $36

-- 2. How many days has each customer visited the restaurant?
Will it change?