# 📘 SQL50 Solutions (MySQL)

This repository contains my solutions to the **LeetCode SQL50** problems, organized by topic.  
I’m solving in **MySQL**, and I’m also posting detailed explanations on my YouTube channel 👉 [Sai Codes](https://www.youtube.com/@saicodes).  

---

## 🟦 SELECT Problems

### 1757. Recyclable and Low Fat Products  
[LeetCode](https://leetcode.com/problems/recyclable-and-low-fat-products/) | [SQL Solution](select/1757_recyclable_and_low_fat_products.sql) | [YouTube](https://www.youtube.com/@saicodes)  

```sql
SELECT product_id
FROM Products
WHERE low_fats = 'Y' AND recyclable = 'Y';
