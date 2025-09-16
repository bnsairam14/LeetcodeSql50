/*
 LeetCode 1757. Recyclable and Low Fat Products
 Link: https://leetcode.com/problems/recyclable-and-low-fat-products/

 Problem:
 Write an SQL query to find the ids of products that are both low fat and recyclable.

 Table: Products
 +-------------+---------+
 | Column Name | Type    |
 +-------------+---------+
 | product_id  | int     |
 | low_fats    | enum    |
 | recyclable  | enum    |
 +-------------+---------+

 Solution Explanation:
 - We need only product_id where both conditions are satisfied.
 - Use WHERE to filter rows where low_fats = 'Y' AND recyclable = 'Y'.

*/

-- ✅ Final Query
SELECT product_id
FROM Products
WHERE low_fats = 'Y' 
  AND recyclable = 'Y';
